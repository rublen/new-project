# new-project

## Instructions

- Create the new public repository "New progect" in you GitHub account
- Clone the rpository to your local machine: git clone <copied path-string from your repository>
- Create an initial README: echo "# new-project" >> README.md
- Commit changes: git add .; git commit -m 'init'
- Rename master branch into main: git branch -m main
- Create the new branch and switch to it: git checkout -b development
- Add instructions to the README.md file
- Commit changes: git add .; git commit -m 'Add instructions to README.md'
- Merge development branch into main branch: git checkout main; git merge development
- Status check: git status
- Push the changes to GitHub: git push -u origin main
