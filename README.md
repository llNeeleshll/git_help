# Git commands which comes handy

### Unadding files
If we want to remove the files we added using

`git add .`

we can use the command

`git reset`

### Uncommit files 
If we've added files using git commit, to uncommit them while making sure that the changes in files remain intact, following is the command.

`git reset --soft HEAD~1`

here '1' represents how many commit you want to go behind.
