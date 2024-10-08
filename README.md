# Git
<br> Version Control System is a tool that helps to track changes in code.
<br> Git is a Version Control Syetem. It is popular,free and open, fast and scalable
# GitHub
<br> Website that allows developer to store and manage their code using Git.
<br> https:github.com
<br> md - Markdown.
<br> Setting up Git-
<br> Visual studio code
<br> windows(Git Bash)
<br> Mac(Terminal)  

# Configuration 
<br> git config --global user.name "My Name"
<br> git config --global user.email "someone@email.com"
<br> git config --list

# Clone and Status
<br> Clone- Cloning a repository on our local machine.
<br> git clone<--some link-->
<br> status- displays the status of the code.
<br> cd--->change directory
<br> cd.. ---> come out of the directory.
<br> mkdir "name" ---> make new directory.
<br> git log --> shows all the log.
<br> q -> quit. 
<br> clear-->clear the terminal
<br> ls--> list the files
<br> ls -a --> shows hidden files.
<br> git status ---> gives the status of the ,file.

# Git Status
<br> untracked -> new files that git doesn't yet track.
<br> modified -> changed.
<br> staged(add file) -> file is ready to commited.
<br> unmodified -> unchnaged.

# Add and Commit
<br>  add -> adds new or changed files in your working directory  to the Git stagging area.
<br> git add<-file name>
<br> commit -> It is the record of change.
<br> git commit -m "some message"

# Push Command
<br> push -> upload local repo content to remote repo
<br> git push origin main

# Init Command
<br> init -> used to create a new git repo
<br> git init 
<br> git remote add origin <-link->
<br> git remote -v    (to verify remote)
<br> git brach        (to check branch) 
<br> git branch -M    (to rename branch)
<br> git push origin  main
<br> git push -u origin main ---> do not need to write origin main again.

# Work Flow
<br> Git repository -> clone ->  changes -> add -> commit -> push.
  
# Git Branches - Branches created when many developer works on a main branch.

# Branch Commands-
<br> git brach   (to check branch)
<br> git branch -M   (to rename branch)
<br> git checkout <- brach name ->   (to navigate)
<br> git checkout -b <-new branch name ->  (to create new branch)
<br> git branch -d <- brach name->  (to delete branch)

# Merging Code
<br> way 1
<br> git diff <-branch name ->   (to compare commits,branches,files & more)
<br> git merge <-branch name ->  (to merge 2 branche)

<br> way 2
<br> create PR.

# Pull Request
<br> It lets you tell others about changes you've pushed to a branch in a repository on GitHub.


# Pull Command
<br> git pull origin main
<br> used to fetch and download content form a remote repo and immediately update the local repo to match that content.

# Resolve Merge Conflicts
<br> An event that takes place when Git is unable to automatically resolve differences in code between two commits.

# Undoing Changes
<br> Case1:staged changes.
<br> git rest <-file name->
<br> git rest

<br> Case2:commited changes(for one commit)
<br> git reset HEAD~1

<br> Case3:commited changes(for many commits)
<br> git reset <-commit hash->
<br> git reset --hard<-commit hash->

# Fork
<br> A fork is a new repository that shares code and visibility setting with the original "upstream" repository.
<br> Fork is a rough copy.