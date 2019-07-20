Reference : [git-scm official documents](https://git-scm.com/book/en/v2)

# git
Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

## Git cli:

<a href="https://ibb.co/XZjyJNg"><img src="https://i.ibb.co/xSXm5P0/git.png" alt="git" border="0"></a>

## Git-scm [Download link](https://git-scm.com/)

## How to push any project in github/bitbucket:
    first create project github/bitbucket:
   
* git init
* git all --all
* git remote add origin https://project-url.git
* git commit -m "commit-message"
* git push -u origin master

## How to pull the project from github/bitbucket:
 ` git clone project-url `
 
## How to create a branch:
` git checkout -b branch-name`

## How to check branch:
` git branch `

## How to go branch:

` git checkout branch-name `

## Remote origin already exists on 'git push' to a new repository
To remove a remote repository

` git remote rm origin `

Again "origin" is the name of the remote repository if you want to remove the "upstream" remote:

` git remote rm upstream `

Reference : [git-scm official documents](https://git-scm.com/book/en/v2)

(See more)[https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-remote.html]
