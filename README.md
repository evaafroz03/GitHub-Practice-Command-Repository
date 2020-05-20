# GitHub-Practice-Command-Repository
Useful git commands

INSTALLATION (FOR LINUX)

Use this command line to install git.

$ sudo apt-get install git

$ git --version (check version after installation successfully)

CONFIGURATION GIT

This command sets the author name and email address respectively to be used with all  repositories.

git config –global user.name "EvaAfroz"

git config –global user.email "EvaAfroz.evaafroz03@gmail.com"

INITIALIZING GIT REPOSITORY 

A Git repository is a virtual storage of your project. It allows you to save versions of your code, which you can access when needed. 

$ git init

$ git add README.md

$ git commit -m "first commit"

git remote add origin https://github.com/evaafroz03/GitHub-Practice-Command-Repository.git

git push -u origin master

CLONE REPOSITORY

To get started, open a terminal window in the directory you wish to clone the repository files into, and run one of the git clone commands git clone <repository path>
  
$ git clone https://github.com/evaafroz03/GitHub-Practice-Command-Repository.git

SWITCHING TO MASTER BRANCH

You are always in a branch when working with Git. The main branch is the master branch, but you can use the same command to switch to a different branch by changing master to the branch name.

$ git checkout master

CREATE A BRANCH

$ git checkout -b <name-of-branch>






