# Git Guide - Basics for Beginners

Initialize git repository
> git init

Add remote repository
> git remote add origin git-url

Create a remote branch with the same name as the local branch and push changes to the remote branch
> git push --set-upstream origin branchname
OR
> git push -u origin branchname
(-u is just a shortcut for --set-upstream)

Create new branch
> git checkout -b branchname

Add all project files to git
> git add .

Commit all files to git with a commit-message
> git commit -m "commit-message"

See list of all branches
> git branch -a

(Click 'q' to quit)

Check current branch
> git branch

Switch to branch
> git checkout branchname

Pull git branch from origin
> git pull origin branchname

Merge branchA into branchB
> git checkout branchB

> git checkout branchA

> git merge branchB

Fetch all branches from remote
> git fetch

Clone repository
> git clone git-url

Delete local git branch
> git branch -D <branchname>
  
