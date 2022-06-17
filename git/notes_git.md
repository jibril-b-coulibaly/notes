**Personal memo of useful Git commands **

git remote update <remote_name> --prune (to update local list of remote branches)
git pull --prune (to update every time)
git config remote.origin.prune true (can be automated with this)

git checkout -b <new_branch_name> <remote_name>/<remote_branch_name> (create local branch from remote branch)

git ls-stree --name-only <branch> (display tracked files)

git reset --soft HEAD^ (to cancel the last commit and keep the changes in the files)

git show <commit> (display content of commit)

git branch -a --contains <commit> (find branches the commit is on)