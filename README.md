# git-started

A toy repo for demonstrating stuff about how to use git

## How to clone this

1. Make sure you have git installed. If on Windows, download and install [Git
   for Windows](https://gitforwindows.org).

2. Open a terminal or Git Bash shell and do:

```
git clone git@github.com:msabramo/git-started.git
```

## How I created this

If you want to replicate what I did, here's what I did:

```
$ cd /some/place/where/I/keep/my/git/repos

$ mkdir git-started

$ cd git-started

$ git init
Initialized empty Git repository in /Users/abramowi/dev/git-repos/git-started/.git/

$ vim numbers.txt
# (type in some stuff)

$ git add numbers.txt

$ git commit -m 'Add numbers.txt'
[master (root-commit) 01a8977] Add numbers.txt
 1 file changed, 14 insertions(+)
 create mode 100644 numbers.txt
```
