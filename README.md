# Git
## Installation 
Go to the [git-scm getting started](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and follow installing on linux/macos/windows section.

## First steps after install
1. Configure your user name `git config --global user.name <username>`
2. Configure your email `git config --global user.email <email>`

## Git cheat sheet
- `git init .` - initialize empty repo in the current dir
- `git clone <url>` - clone git repo from url. Url usually should looks like `https://..`, `ssh://git@....`, or `git@...`
- `git diff` - see what you have changed
- `git add .` - add changes to the git stage
- `git add . -N` - usefull command to add completely new files to the git scope (but not stage), so you can see them with `git diff`
- `git commit` - commit changes
