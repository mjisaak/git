# Working with git using the command line

## Clone a Github repository:
    git clone https://github.com/mjisaak/git.git


## Retrieve git status:
    git status


## Stage files for the next commit:
    git add .

## Commit staged files:
    git commit -m "added content"

## Push local commits to the remote repository:
    git push

## List remote repositories
    git remote show origin
Output:
    origin

## List remote repository url
    git remote show origin
Output:
```
* remote origin
Fetch URL: https://github.com/mjisaak/git.git
Push  URL: https://github.com/mjisaak/git.git
HEAD branch: master
Remote branch:
    master tracked
Local branch configured for 'git pull':
    master merges with remote master
Local ref configured for 'git push':
    master pushes to master (up to date)
```