# Navigation
pwd
ls
cd <directory_name>
clear

# Repository Management
mkdir git-for-devops
git init

# File Operations
touch nibba.txt nibbi.txt
vim <file_name>
cat <file_name>
ls -l
rm <file_name>

# Git Status and Changes
git status
git add <file_name>
git commit -m "<commit_message>"
git rm --cached <file_name>
git restore <file_name>

# Branching
git checkout -b <branch_name>
git checkout <branch_name>
git branch

# Viewing History
git log
git log --oneline

# Configuration
git config --global user.name "<your_name>"
git config --global user.email "<your_email>"

# Working with Remote Repositories
git fetch <remote_name>
git push <remote_name> <branch_name>
git pull <remote_name> <branch_name>
