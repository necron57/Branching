# Git Cheat Sheet

## Basic commands
* `git init` - initialize a local Git repo
* `git branch -m branchname` - rename current branch to `branchName`
* `git add . ` -  stage all files in current folder for commit
* `gti commit -m "msg"` - commit staged files with commit message

## info commands
* `git status` - show status of working directory
* `git log` - list commit history of local repo
* `git log --oneline` -  compact commit history

## branching commands
* `git branch` - list local branches
* `git branch branchname` - create new branch `branchname`
* `git checkout branchname` - move to local branch `branchname`

* `git checkout -b branchname` -  create branch and check it out

## Remote commands
* `git remote add origin URL` - connect local repo to remote repo URL with alias `origin`
* `git pull origin main` - pull remote branch `main` into local current branch
* `git pull origin branchName` - pull remote branch into local current branch
*

