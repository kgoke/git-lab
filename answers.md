Keegan Goecke 
CS 2400

1.)
 git version 2.33.0.windows.1

2.) 
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Keegan Goecke
user.email=kg333920@ohio.edu

3.)
It opened up the git-add(1)manual page below.
file:///C:/Program%20Files/Git/mingw64/share/doc/git-doc/git-add.html

4.)
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

5.)
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

6.)
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

7.)
On branch master
nothing to commit, working tree clean

8.)
commit eb63d75cd3a9c6b356304bd19527202fb363b324 (HEAD -> master)
Author: Keegan Goecke <kg333920@ohio.edu>
Date:   Fri Sep 3 14:31:59 2021 -0400

    Initial commit

9.)
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 849 bytes | 849.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/kgoke/git-lab.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

10.)
The changes made online were not reflected in my local copy.

11.)
when i used the command git push i got the error message below.
To https://github.com/kgoke/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/kgoke/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

12.)
After using the command "git pull" the changes made online reflected into my local copy.

13.
Directory: C:\Users\Kmgoe\2400\git-lab-2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          9/3/2021   3:14 PM            302 .gitignore
-a----          9/3/2021   3:14 PM             11 README.md

14.)
