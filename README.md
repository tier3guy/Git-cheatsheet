# Git Cheatsheet
##### ❤ Git is a distributed version control system that helps developers collaborate on projects of any scale.

## What is a Distributed Version Control System?

- A distributed version control system is a system that helps you keep track of changes you've made to files in your project.
- This change history lives on your local machine and lets you revert to a previous version of your project with ease in case something goes wrong.
- Git makes collaboration easy. Everyone on the team can keep a full backup of the repositories they're working on on their local machine. Then, thanks to an external server like BitBucket, GitHub or GitLab, they can safely store the repository in a single place.

## Installation
[https://git-scm.com/downloads] Go to this website and simply click on the git for windows or mac as per your computer and just install it by clicking the next-next button. 😎

## Commands 🐱‍👤

`-- Initializing git Repository`
```sh
git init <directory>
```

`-- Seting up your Git username and email ID`
```sh
git config --global user.name "Avinash Gupta"
git config --global user.email "example123@gmail.com"
```

`-- Adding a file to the staging area in Git:`
```sh
git add filename_here

'Suppose there are mutiple files then instead of adding files individually you can use '
git add .
```

`-- Checking a repository's status in Git`
```sh
git status
```

`-- Commit changes in the editor in Git`
```sh
git commit

'Now imagine a situation that you want to commit a change but you also want add some message with that, so that in future you must understand why you commited that message then use,'

git commit -m "you message here"
```

`-- Your commit history`
```sh
git log
```

`-- Specific commit history`
```sh
git show commit-id
```

`-- Undoing commit`
```sh
git revert <commit>
```

`-- Creating new branch in the repository`
```sh
git branch branch_name

'showing all the branches in the repository'
git branch

'Moving one branch to other'
git checkout branch_name

'Deleting a branch in Git'
git branch -d branch_name

'Merging two branches in Git'
git merge branch_name
```

`-- Adding remote`
```sh

git remote add <name> <url>

'Fetching a specific <branch>, from the repo. Leave off <branch>
to fetch all remote refs'
git fetch <remote> <branch>

'Fetching the specified remote’s copy of current branch and
immediately merge it into the local copy'
git pull <remote>

'Push the branch to <remote>, along with necessary commits and
objects. Creates named branch in the remote repo if it doesn’t exist'
git push <remote> <branch> 

```

#### Downloadable cheatsheet
[https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet]

#### More beautiful documentation
[https://www.freecodecamp.org/news/git-cheat-sheet/]

### People are also requested to add more commands what you think is important and I have'nt added it you please git-add-those-commands.
## Dhanyawad 🙏
