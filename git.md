# Git cheat sheet
## Configure the git directory

Configure name `git config --global user.name <name>`

Configure email `git config --global user.email <email address>`

Initialize the git folder`git init`

To clone an existing repository `git clone <repository URL>`

## Git every day uses
To include a file for staging `git add <file>`

include all update: `-u`

include all: `-a`     

To remove a staged file: `git reset <file>`

To prepare a commit `git commit -m <commit message>`

## Git migrating the repository

To have an exact copy of the git repository `git clone --mirror [gitlink]`

To change the branch name (from master to main for github) `git branch -m master main`

To push the repository to the new address `git push --no-verify --mirror [gitlink]`


## Remove a file from the git repository
Remove a file from the whole git repository, use the package `git-filter-repo`
then use command `git filter-repo --invert-paths --path <filename to be removed>`
