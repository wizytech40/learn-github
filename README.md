# Initializing a git repository

> git init

This initializes the parent folder to be a git repository.

> git status

checks the status of the tracked directory

> git add .

adding all untracked files to git repository locally.

> git restore --stagged "_the name of the file ypu want to remove from the git local repo_/ . ~removing all~"

> git commit -m "_the commit message_"

This commits the added local files from >> git add

> git log

checks the commited file/tracked

> git show "_the uid of the file commited_"

showing the changes from a specific selected commit

> git branch -M main

changing the local master branch to the _MAIN BRANCH_ used by Github.

> git remote add -u origin "http://git.github.com"

adding a remote origin

> git push -u origin main

for pushing the code to be tracked by the remote git repository

> git pull

pulls the made changed from github to our local repository.

## Branches

> git branch

checks the branch which you are in

> git branch -a

checks the local branches

> git branch -r

checks remote git branches for the repository

> git branch "_branch name_"

creates a branch specified in the branch name.

> git checkout "_branch name_"

switches from the main the main branch to your specified created branch.

> git checkout -

switches from the specified branch to the main branch

> git branch -b "_branch name_"

creates a branch and switches to it directly

> git branch -d "_branch name_"

deletes the specified branch.
