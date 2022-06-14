# Solution

Complete each task. Then, follow the instructions as to what to copy and paste into the empty code block.

> **Note:** Carefully read the instructions for each task. Sometimes you will be asked to record the _command(s)_ you wrote while other times you will be asked to record the _output_ of the command you wrote.

## 1

Create a new directory called `git-lab/`. Then, navigate inside of that directory.

Copy and paste _the command(s)_ you used into the code block below.
git git-lab                       module-one
introductory-command-line-lab variables
introductory-javascript
➜  9.1 cd git lab
cd: string not in pwd: git
➜  9.1 cd git-lab
➜  git-lab ls
➜  git-lab history | tail -n 10
 1348  history | tail -n 10
 1349  cd
 1350  clear
 1351  cd 9.1
 1352  ls
 1353  `mkdir git-lab/`.
 1354  ls
 1355  cd git lab
 1356  cd git-lab
 1357  ls
```

```

## 2

Initialize the directory as a git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

`` git-lab git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint: 	git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint: 	git branch -m <name>
Initialized empty Git repository in /Users/shaqualafredericks/9.1/git-lab/.git/
➜  git-lab git:(master)`

```

## 3

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

`git-lab git:(master) git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
➜  git-lab git:(master)``

```

## 4

Create a new file called `readme.md`. Then stage that file.

Copy and paste _the command(s)_ you used into the code block below.
➜  git-lab git:(master) `touch readme.md`.
.: not enough arguments
➜  git-lab git:(master) ✗ ls
readme.md
➜  git-lab git:(master) ✗ git status
On branch master

No commits yet
```

```

## 5

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.
 git-lab git:(master) ✗ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	readme.md

nothing added to commit but untracked files present (use "git add" to track)
➜  git-lab git:(master) ✗ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	readme.md

nothing added to commit but untracked files present (use "git add" to track)
➜  git-lab git:(master) ✗
```

```

## 6

Add the following text to your `readme.md` file.

```
I am learning to use git.
```

Then, check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   readme.md

➜  git-lab git:(master) ✗ git commit -m "I am learning to use git"
[master (root-commit) 0191298] I am learning to use git
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md
➜  git-lab git:(master) git status
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master)
```

```

## 7
  git-lab git:(master) git commit -m "Javascript is fun once you get it"
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master) git status
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master) git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
	add
➜  git-lab git:(master) git add src
fatal: pathspec 'src' did not match any files
➜  git-lab git:(master) git status
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master)
Commit your changes and include a sensible commit message. Then, check your repository's history.

Copy and paste _the command(s)_ you used into the code block below.

```

```

## 8

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.
 git-lab git:(master) git commit -m " Pursuit has the best programs"
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master) git status
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master) git status
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master)
```

```

## 9

Stage your changes and then make another commit with a sensible commit message.

Copy and paste _the command(s)_ you used into the code block below.
git-lab git:(master) git status
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master) git status
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master) git commit -m " This Excercise was a bit confusing"
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master) git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
	add
➜  git-lab git:(master) git add -A
➜  git-lab git:(master) git add src
fatal: pathspec 'src' did not match any files
➜  git-lab git:(master) git status
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master) git add-A
git: 'add-A' is not a git command. See 'git --help'.
➜  git-lab git:(master) git add -A
➜  git-lab git:(master) git commit -m "This Excercise was a bit confusing"
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master) git status
On branch master
nothing to commit, working tree clean
➜  git-lab git:(master) ls
readme.md
➜  git-lab git:(master)
```

```
