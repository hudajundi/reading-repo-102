# Git Tutorial
## Setting up a Git Repository
### Importing 
Use the command line to follow these steps:
1. cd test (cd = change directory) 
2. $git init
3. $ git add *.c
4. $ git add LICENSE
5. $ git commit -m “any message here”
### claoning
create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL
## Workflow 
### Local Repository Structure
* **Working Directory**: The actual files reside here.
* **Index**: The area used for staging
* **Head**: Points to the most recent commit
### Saving Changes
* Tracked (*Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.*)
* Untracked(*Untracked files were not in the last snapshot and do not currently reside in the staging area.*)
### commiting
* **commiting a file**  commit the changes and record what you did within the commit message: *$ git commit -m “made change x,y,z”*
* **Committing All Changes** commits a snapshot of all modifications to tracked files 
