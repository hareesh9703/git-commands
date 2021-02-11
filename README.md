# git-commands
git branch <branch-name>
  This command will create a branch locally. To push the new branch into the remote repository, you need to use the following command:

git push -u <remote> <branch-name>
Viewing branches:

git branch or git branch --list
Deleting a branch:

git branch -d <branch-name>
3. Git checkout
This is also one of the most used Git commands. To work in a branch, first you need to switch to it. We use git checkout mostly for switching from one branch to another. We can also use it for checking out files and commits.

git checkout <name-of-your-branch>
There are some steps you need to follow for successfully switching between branches:

The changes in your current branch must be committed or stashed before you switch
The branch you want to check out should exist in your local
There is also a shortcut command that allows you to create and switch to a branch at the same time:

git checkout -b <name-of-your-branch>
This command creates a new branch in your local (-b stands for branch) and checks the branch out to new right after it has been created.

4. Git status
The Git status command gives us all the necessary information about the current branch. 

git status
We can gather information like:

Whether the current branch is up to date
Whether there is anything to commit, push or pull
Whether there are files staged, unstaged or untracked
Whether there are files created, modified or deleted
git add <file>
To add everything at once:

git add -A
