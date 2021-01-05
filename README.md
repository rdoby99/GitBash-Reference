# GitBash-Reference

## Useful commands
- `cd` navigate to your home directory or change directories
- `cd ..` navigate up one directory level
- `cd-` navigate to the previous directory
- `cd /` navigate into the root directory
- `git status` the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git
- `ls`  lists files and directories within the file system
- use insert button to paste
- `start <FILE NAME>` open a file in text editor/VS Code
- `touch <FILE NAME>` creates a file

## Create a Branch
- Clone a repository: `git clone <REPOSITORY URL>`
- Go to repo: `cd <REPO NAME>`
- Create a branch: `git branch <BRANCH NAME>`
- Push branch to Github: `git push --set-upstream origin <BRANCH NAME>`

## Make a Commit
- Check out to a branch: `git checkout <BRANCH NAME>
- Create a file `touch <FILE NAME>`
- Make changes to file, save
- Stage the file: `git add <FILE NAME>`
- Commit change: `git commit -m "<COMMIT MESSAGE>"`
- Push commit to GitHub: `git push`
