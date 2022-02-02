# gitcheatsheet
Git cheatsheets
=================================================
1. Git Configurations
     $ git config --global user.name "your name"

    $ git config --global user.email "your email.com"

   $ git config --global color.ui auto

------------------------------------------------
2. Git installation

  $ sudo apt-get install git

-----------------------------------
3. Ignoring Files

    $ cat .gitignore

    /logs/*

    !logs/.gitkeep

    /tmp/

    *.swp
---------------------------------------------------------------------
4. Starting A Project

    $ git init [project name]

    $ git clone [project url]

    $ git rm [file]

    $ git stash

  Put current changes in your working directory into stash for later use.

    $ git stash pop

   Apply stored stash content into working directory, and clear stash

   $ git stash drop

   Delete a specific stash from all your previous stashes
-----------------------------------------------------------------------
5. Git branching model

    $ git branch -a

    show all branches

    $ git branch [branch name]

    Referencing current branch

    $ git checkout -b [branch name]

    Git will create the specified branch if it doesn't exit.

    $ git merge [from name]

    $ git branch -d [name]

    delete branch
 --------------------------------------------------------
 6. Day to day work

     $ git status

     $ git add [file]

     $ git diff [file]

     $ git diff --staged [file]

     $ git checkout --[file]

     $ git reset [file]

     $ git commit

 ------------------------------------
 7. Review your work

     $ git log [-n count]

     $ git log --online --graph --decorate

     $ git log ref..

     $ git log --ref

     $ git reflog
 ----------------------------------
 8. Synchronizing repositories

     $ git fetch [remote]

     $ git pull [remote]

     $ git fetch --prube [remote]

     $ git push [--tags] [remote]

     $ git push -u [remote] [branch]

 ==================================
