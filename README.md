GVPW@DESKTOP-EOOCFAR MINGW64 ~
$ git clone https://github.com/kancharlanihari84/Devops-Lab.git
Cloning into 'Devops-Lab'...
warning: You appear to have cloned an empty repository.

GVPW@DESKTOP-EOOCFAR MINGW64 ~
$ cd Devops-Lab

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ echo "my first repository file"
my first repository file

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ echo "my first repository file">sample.txt

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        sample.txt

nothing added to commit but untracked files present (use "git add" to track)

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git add sample.txt
warning: in the working copy of 'sample.txt', LF will be replaced by CRLF the next time Git touches
it

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git add .

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   sample.txt


GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git commit -m "added sample.txt"
[main (root-commit) a11c1b2] added sample.txt
 1 file changed, 1 insertion(+)
 create mode 100644 sample.txt

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git push origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 246 bytes | 246.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kancharlanihari84/Devops-Lab.git
x* [new branch]      main -> main

x

x



xVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
x



GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git commit -m "added sample.txt"x
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean




GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git credential-manager erase
protocol=https
host=github.com


GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git config --global user.name
jahnavi

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git config --global user.name "kancharlanihari84"

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git config --global user.email "324103210084.nihari@gvpcew.ac.in"

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git config --global user.name
kancharlanihari84

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git config --global user.email
324103210084.nihari@gvpcew.ac.in

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ sample.txt
bash: sample.txt: command not found

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ ls
sample.txt

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ cat sample.txt
my first repository file

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ git log --oneline
a11c1b2 (HEAD -> main, origin/main) added sample.txt

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$ ls
sample.txt

GVPW@DESKTOP-EOOCFAR MINGW64 ~/Devops-Lab (main)
$
