

What is a Repository?
My definition for this command is captured in red font in the screenshot below.
 
The below shows the created content of a Repository File or Folder


### GitFlow workflow

It is a tree-like architecture or a file structure that Git uses, where there is a reporsitory and a working copy of that repository. In order to move files between the repository and a working copy, 
 

### Repository:
After Git has been installed and configured, next is to put Git in the appropriate condition to start its operation. That is asking Git to start tracking changes in a particular project. We need to however decide where to put the project for Git to start tracking. This location is called a Repository. The repository can be a new folder created in a Windows directory on a Desktop.

The folder can be accessed via the command line by changing in to the windows directory in which that folder was created. Once in the root of the folder via the command Line, entering - Git init will tell Git to get everything ready to start doing its tracking.

A repository can also be created in the User Interface from the home screen after signing into your account, and then selecting 'New' or the 'Plus' sign (+) on the top right corner of the home page. See file attachment called 'Create a new repository.

![Screenshot added on creating a new repository](https://raw.githubusercontent.com/pyruskimo/LarryTaiyeImages/master/TestImage1.PNG)


        Instead of using a single server-side repository to act as the “central” codebase, forking gives every developer a server-side repository. This means that each contributor has not one, but two Git repositories: a private local one and a public server-side one.
        
 
## Clone
A clone is a copy or the act of making a copy of a repository, for example, a copy of the the master branch. When a clone is made, files can be edited and Git will track the different changes made. The repository that was cloned is still connected to the remote version such that that changes that were made locally can be pushed to the remote to keep them synced.

## Branch:
A branch represents an independent line of development. It is thought of as a way to request a brand new working directory, staging area, and project history. New commits are recorded in the history for the current branch, which results in a fork in the history of the project.
Getting the most out of Git will mean using branches often and effectively. Branches are easy to create, work with, delete and allow testing of different ideas. Assuming working on a project, and suddenly an idea comes to mind. Though uncertain if the new idea will work or not, instead of making lots of commit to the master branche and undoing <del>or reverting</del> the changes, a new branch can be created and the new idea test there on. And if the ideas do not work, the branch can be deleted and the master branch would not have been affected by the chnages. However if the idea does workout, those changes can be brought back to the master branch through a process called merging.



## Commit: 
Commit implies telling Git to track the individual change to a file (or set of files). When a commit is made to save a work, Git creates a unique ID called "hash" that allows the keeping of record of the specific changes commited along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made 


 
## Merge
Merging is a way of combining the work from two different branches together where a branch was created to develop a new feature and then combined back in to the main branch or master branch.


## Checkout

## Push
The git push command is used to upload local repository content to a remote repository. Pushing is how commits are transfered from a  local repository on to a remote repository.
- It uses the following command: git push <remote> <branch>
 
 



## Pull 

## Remote
Remote allows us to collaborate with others.
      Remote Add / Remove / Show
Status
Master Branch





- [x] Repository
- [ ] Clone
- [ ] Fork
- [x] Branch
- [x] Commit
- [ ] Merge
- [ ] Checkout
- [ ] Push
- [ ] Pull
- [ ] Remote

        Add
        
        Remove
        
        Show
        
- [ ] Status
- [ ] Master branch



[Reference](https://guides.github.com/introduction/git-handbook/)

[Reference](https://www.atlassian.com/git/tutorials/using-branches)

[Reference](https://www.atlassian.com/git/tutorials/saving-changes/git-commit)

[Reference](https://www.atlassian.com/git/tutorials)
