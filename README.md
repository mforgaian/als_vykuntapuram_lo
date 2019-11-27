
# Frequently Used commands in GIT

* Initiate local git repo
```
git init
```

* Add untracked files to stage
```
git add .
```
or 
```
git add file_name
```

* Commit changes in stage
```
git commit -m "message"
```
* commit changes untracked and stage
```
git commit -am "message"
```

* stash
```
git stash
```
* list stashed changes
```
git stash list
```
* apply recent stashed changes
```
git stash apply
```

* list all branches
```
git branch
```

* checkout to new branche
```
git checkout -b new_branch_name
```

* checkout to existing branch
```
git checkout existing_branch_name
```

* see previous commits
```
git log 
```

* see logs in oneline
```
git log --oneline
```

* decorate and plot logs along with branching strategy
```
git log --graph --oneline --decorate
```

* Push local changes of current branch to remote
```
git push 
```

* Pull latest changes from remote current branch to local
```
git pull
```

* merge changes from another branch
```
git merge another_branch
```
* Check the status of current branch, untracked files, staged files etc.
```
git status
```

