Git Documentation:
To collaborate, Download Git and Git-Bash on your machine which is used to clone the project from central repository.
Step 1: Clone the project - creates project folder under the current directory:
  git clone https://github.com/vijender007/never-mind-it.git
Step 2: Pull the repository for any modifications - to get current state
  git pull
Step 3: Create a branch to work on - Should not change the master
  git checkout -b branch-name
Step 4: Add the files to commit - add only the files which needs to be added
  git add file-names OR git add -A (to add all the file changes)
Step 5: commit the changes on the branch - can have multiple commits on branch
  git commit -m 'message-text'
Step 6: Push to git hub after modifications - changes to branch should go to git hub
  git push --set-upstream origin branch-name

On git hub, We will be reviewing changes on the branch and if everything looks good, will be merge changes to master.
At this point, master will have all the changes in master.

To navigate between branches
  git checkout 'brach-name' 

Download links and documentation:
https://git-scm.com/downloads
https://git-scm.com/doc
