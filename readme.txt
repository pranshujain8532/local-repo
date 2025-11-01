PS D:\coding\github> git init   
Initialized empty Git repository in D:/coding/github/.git/
PS D:\coding\github> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.css
        index.html

nothing added to commit but untracked files present (use "git add" to track)
PS D:\coding\github> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.css
        index.html

nothing added to commit but untracked files present (use "git add" to track)
PS D:\coding\github> git add --a
PS D:\coding\github> git status 
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.css
        new file:   index.html

PS D:\coding\github> git commit -m "initialised"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Acer@LAPTOP-F30D92GE.(none)')
PS D:\coding\github> git config --global user.name "Pranshu"
PS D:\coding\github> git config --global user.email "pranshujain8532@gmail.com"
PS D:\coding\github> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.css
        new file:   index.html

PS D:\coding\github> git commit -m "initialised"
[master (root-commit) 151a1ed] initialised
 2 files changed, 4 insertions(+)
 create mode 100644 index.css
 create mode 100644 index.html
PS D:\coding\github> git status
On branch master
nothing to commit, working tree clean
PS D:\coding\github> git remote add origin https://github.com/pranshujain8532/local-repo.git
PS D:\coding\github> git remote -v
origin  https://github.com/pranshujain8532/local-repo.git (fetch)
origin  https://github.com/pranshujain8532/local-repo.git (push)
PS D:\coding\github> git branch
* master
PS D:\coding\github> git branch -M main
PS D:\coding\github> git branch        
* main
PS D:\coding\github> git push -u origin main
fatal: unable to access 'https://github.com/pranshujain8532/local-repo.git/': Could not resolve host: github.com
PS D:\coding\github> git push origin main   
fatal: unable to access 'https://github.com/pranshujain8532/local-repo.git/': Could not resolve host: github.com