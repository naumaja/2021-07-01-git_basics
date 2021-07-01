<<<<<<< HEAD
# 2021-07-01-git_basics
=======
>>>>>>> 54c3999610044c2001d84ea9cd7922e094ad5bee

- `git init`: initialize git repository in current working directory
- `git status`: gives you status of current repository
- `git add <FILE>`: adds <FILE> to the staging area
- `git commit`: creates a commit, you provide message
- `git log`: shows you the log of your commits
	- `git log --oneline`: shos you the one line version of the log


- `git config --list`: shows list of config 

- `HEAD': where you currently are (the version of the files on your computer)
- `git diff HEAD~<NUM> <FILE>`: compares current file to file <NUM> ago
	- `git diff <HASH> <FILE>`: compares current file to <HASH> version

- `git checkout <HASH> <FILE>`: restore <FILE> to version in <HASH>
- Use `git status` to help you find the commands to unstage or restore <FILE>
	- if you run `git checkout <HASH> without the <FILE>
	- you can fix this be running `git checkout main`


- git ignores empty folders
- use `.gitkeep` to "keep" an empty folder
- use `.gitignore` to ignore files/patterns

<<<<<<< HEAD
# Remotes
>>>>>>> 54c3999610044c2001d84ea9cd7922e094ad5bee
	
- `ssh-keygen`: to create ssh keys
- `git remote add <URL>`: adds the url	
- `git push origin main`: push the main branch to the origin remote
- `git pull origin main`: pull the main branch from the origin remote

