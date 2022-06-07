# Basic_Git_commands
| Command | Description |
| --- | --- |
| `rm -rf .git` | Remove git directory from react app |
| `git reset filename/foldername` | Undo git add command if git commit not used |
| `git init` | Initialise an existing directory as a Git repository |
| `git clone` | creates a local copy of a project that already exists remotely. The clone includes all the project's files, history, and branches. |
| `git add file.txt` | Tell git to start tracking changes to the file file.txt |
|`git add file1.txt file2.txt file3.txt `| Tell git to start tracking changes to the file file1.txt file2.txt file3.txt |
|`git add directory `| Tell git to start tracking changes to all the .csv files in the folder with the name directory |
|`git commit -m "message for the commit" `| Create a new commit containing any changes to the previously added files with the mentioned message |
|` git remote add origin https://github.com/username/test.git `|Add a git URL as a remote |
|`git push origin master `| Transmit local commits to the remote repository |
|`git clone https://github.com/username/test.git`| retrieves an entire repository from a hosted location via URL|
|`git pull origin master `|Fetch and merge any commits from the tracking remote branch |
|`  git status`| show modified files in working directory, staged for your next commit|
## Git branch commands
| Command | Description |
| --- | --- |
| ` git branch --list` | List all the branch in the repo |
| `git branch <name>` | Create a new branch with the given name. |
| `git branch -m <new_name> ` | Rename the branch to with the new name |
| `git checkout <branch_name>` |  Switching to the new branch name|
| `git push origin <branch_name>` | Push a particular branch to the remote repo |




