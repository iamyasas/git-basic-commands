# git-basic-commands
Since I got limited memory ;)
This is to make a note of the git commands I use it & refer later.

1) git init - initialize a git repo (exisiting code/ empty)

2) git add . - add/stage current directory
3) git commit -m "initial commit" - commit the repo
5) git commit -a -m "add and commit" - add/stage and commit(1+2)

4) git remote (-v) - show remote repos
5) git remote add origin htttps://your-remote-git-repo.git - add remote repo 'origin'
6) git remote show origin - show remote repo 'origin' information

7) git push -u origin branch-name - push local branch 'branch-name' to the remote repo 'origin' and set as upstream (TO BE USED WHEN UPSTREAM IS NOT SET)
8) git push - push local branch to remote (TO BE USED WHEN UPSTREAM IS SET)

9) git branch -a - show branches
10) git branch branch-name - create a new branch from last checkedout branch named 'branch-name'
11) git checkout branch-name - switch to the 'branch-name' branch.
12) git checkout -b branch-name - create and switch(11+12)

13) git merge branch-name - merge 'branch-name' with checkedout branch
14) git fetch - Sync local with remote(new branches and commits will sync with local)
