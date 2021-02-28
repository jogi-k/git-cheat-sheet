# git-cheat-sheet
git commands which I need sometimes in my shared workflow and which I usually don't remember

## Update from remote repos
* ```git fetch --prune```
* ```git rebase```

Now ```git status``` should tell everything fine, maybe the submodule is not updated

## Update submodule
* ```git submodule update --init```

Now ```git status``` should tell everything fine

## Update a submodule to an pending PR or new master
* ```cd <submodule-dir> ```
* ```git checkout [master|<pending_pr_branch>] ```
* ```cd ..```
* ```git add <submodule-dir> ```
* ```git commit -m "Update submodule <submodule-dir> to branch / master ```


