# git-task
Git Learnable Assignment

## Table of Contents
- [Version Control](#version_control)
- [Git and Github](#difference_git_github)
- [Github Alternative](#github_alternative)
- [Git Fetch and Git Pull](#git_fetch_&_git_pull)
- [Git Rebase](#git_rebase)
- [Git Cherry-pick](#git_cherry-pick)
- [Usage](#usage)

## Version Control
Version control can be best describe as a system that records and control changes to a file o set of file over time, so that specific version can be recalled later. Poopular version control syste are Git and Mercury.

## Git and Github
Git is a popular version control system, used for tracking code changes, tracking who made changes,  coding collaboration during software development WHILE Github is a code hosting  platform for version control and collaboration, which let users work together on project from anywhere.
In summary Git is the tool WHILE Github is the platform that makes use of Git.

## Github Alternative
3 other Github Alternative are
- GitLab
- Bitbucket
- SourceForge

## Git Fetch and Git Pull
Git Fetch allows user to retrieves changes from a repository without merging it into current working branch WHILE Git Pull allows  user to fetch annd merge the fetched into the current branch. In summary, the Git Fetch is just for inspecting changes WHILE the Git Pull, inspect the changes and merge it immediately to the current branch.

## Git Rebase
It is a simple  command used to integrate changes from one branch into another branch, including the commit history.

For Example

I have 2 branch- feature and dev 
Use

"git branch" 

to check and make sure we currently in our "feature" branch and also our "dev" branch exist, since we want  to integrate it to our "dev" branch, then we use

"git rebase dev"

with that the rebase is complete, git has written the commits from our "feature" branch onto the most recent commit onto the "dev" branch.

## Git Cherry-pick
It is a simple command that allows users to apply a specific commit from one branch to another branch. Its very important for users that make a commit to the wrong branch, they can easyly get those changes onto the correct branch without redoing all that work  again 

For Example

switch to the branch  i want to  commit from
check for the Id of the specific commit from "git log", 
switch back to the destination branch, then execute

"git cherry-pick a657463646"

then it will commit the changes to the destination branch, by creating a new commit to the branch.
Aalso for multiple commit, by just adding the id one after the other 
eg

"git cherry-pick a657463646 a657463647 a657463648"

## Usage

To get started with this project, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/samdova/git-task.git

2. **Navigate to Project Directory**
    Open your editor
    Open folder named "git-task" from your download directory