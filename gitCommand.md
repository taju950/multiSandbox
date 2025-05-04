# Git file to demonstrate the use of git.


## Git common used commands:
These are not the only used common used commands but the most used commands.

### 1 git clone :
- it is used to clone local repository
- i## 2 git version t need url and user id to push or pull

### 2 git version :
- it is used to know the version we have

### 3 git config :
- it is used to configure repository
- git config --global user.name "Your Name"
- git config user.email "[email protected]"

### 4 git status :
- it's used to view status

### 5 git add :
- it is used to add changes

### 6 git branch :
- it is used to know which branch 

### 7 git push origin main :
- it is used to push repository

### 8 git commit:
- it is used to commit repository changes
- git commit -m "Your commit message describing the changes"

### 9 git -- help:
- used to ask help 



<hr>
## Common uses:

### how to save changes in file:
- Use "git status" to view the changes or if there are any changes to be comited or to be pulled.
- Then use "git add" to add your changes. (add is to let git know that to consider the changes and add the changes.)
- Use "git commit -m "Commit message"" to commit changes. (Commit means to confirm the changes are correct and can be staged.)
- Use "git push" to push the changes to the changes to the gitHub.




## How to clone a project or repository from github into my system:
Steps for cloning a project into a directory:
	step 1:navigate to the directory(folder) where you want to clone in terminal
	step 2: write git clone command with the link which is found in git project
	Example: git clone https://github.com/taju950/multiSandbox.git


## How to save provided  token for git push:
git remote set-url origin https://<tocken>@github.com/<username>/<repo_name>

## Use of git add:
The git add command is used to stage changes in your project so they’re ready to be committed. Think of it as telling Git, "I want to include these changes in my next snapshot."
Example:git add <file-name>

## Use of git commit:
The git commit command is used to save your staged changes as a new snapshot in your local Git repository.
Each commit acts as a "save point" in your project’s history, making it easy to track and revert changes if needed.
Example: git commit -m "Your descriptive commit message"

## use of git push:
The git push command uploads your local commits to a remote repository, such as GitHub, so others can see and collaborate on your work. Here’s how to use it:

git push <REMOTE-NAME> <BRANCH-NAME>
<REMOTE-NAME> is usually origin (the default name for your remote repository).
<BRANCH-NAME> is the branch you want to push, such as main or master
Example:git push origin main







