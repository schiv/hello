1) generate repository online
start new project on github.com
schiv/hello

2) configure your local git
$ git config --global --edit
----------------------------------------------------------- 
# This is Git's per-user configuration file.
[user]
# Please adapt and uncomment the following lines:
name  = schiv
email = schiv@users.noreply.github.com
-----------------------------------------------------------
$ git commit --amend --reset-author

3a) create a new repository on the command line
$ echo "# hello" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ 3b push an existing repository

3b) push an existing repository from the command line
$ git remote add origin https://github.com/schiv/hello.git
$ git push -u origin master

3c) checkout an online repository
// $ git clone schiv@github.com:/hello
$ git clone https://github.com/schiv/hello.git

4) do your work
change to new directory ./hello
work on the files ...

5) suggest a change
$ git add commanline.md
