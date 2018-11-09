# Untrack a single file that has already been added/initialized to repository, i.e., stop tracking the file but not delete it from system use 
Syntax: `git rm --cached <filename>`
Example: `git rm --cached Pipfile.lock`
# Force “git pull” to overwrite local files
1. Download the latest code from remote without trying to merge or rebase anything:
`git fetch --all`
2. Reset the master branch to what is fetched. Add `--hard` option to change all the files in working tree to match the files:
Syntax: `git reset --hard origin/<branch_name>`
Example: `git reset --hard origin/master`
