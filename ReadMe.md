Local
working directory(locally we do changes here--git add takes us to staging area)
staging area(git commit -m "write message" , this one takes our code to local repo, )
local repository(here we can trap the changes by the commit id)--here we do git push which takes to remote repo

Remote
remote repository(online github)
----
git init=initialise your repository with git and git starts tracking your changes in the file
git status=tells us in which files the changes took place
git add filename=adds file to staging area
git commit -m "write message"=commit a file to commit history
git remote add [remote repository name] [remote url]=conects local repository to a remote repository
git push [remote url]=push the local repository to remote
----
git clone [url]=clone the remote repo to a local repo
mkdir=make new directory
ls=list all the files and folder
pwd=shows the current directory
cd=change directory
----
git diff --staged=shows difference between previous commit and current working directory
git log=gives the log, shows all your commits with commit id
git checkout [commit id]=commit id is the first five characters of the id
git branch=shows all the branches in the local repository
git checkout [branch name]=to switch to a particular branch
git branch [branch name]=to create a new branch
git diff [branchA] [branchB]=to see the difference between the branches
-- by default the branch is master
----
open source project=initiated by a developer or a group of developers and later made it open so that anyone can contribute to its developmnet and maintainance,such projects are made by collabrative efforts by several people. Eg-firefox webbrowser, Vlc media player, etc.
