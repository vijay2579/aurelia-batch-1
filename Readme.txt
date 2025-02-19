// Setting usename
git config --global user.name "username"
git config --global user.name

git config --global user.email "email"
git config --global user.email

git status // List down all modified or newly added files/folder
git branch // List down all available branches

git clone repo_url // Cloning/copying repository from github

// Pushing changes to the remore repository
git add . // All modified files/folders to the staging area
git commit -m "Initial commit" // Files/folders which are ready to be pushed to the remote repository
git push origin BRANCH_NAME // For pushing local changes to the remote repository

// Creating New branch
git branch BRANCH_NAME // create a new branch
git checkout BRANCH_NAME // gets into the specified branch

git pull origin BRANCH_NAME // Pulling latest changes from remote repository to local repositiory

git stash // Copy the changes to the clipboard
git stash apply // Restore the changes to the branch

git diff // Show the differences between existing Vs modified changes for all files
git diff FILE_PATH // Show the differences between existing Vs modified changes for the mentioned FILE_PATH

git branch -d BRANCH_NAME // deletes branch if merged with main branch
git branch -D BRANCH_NAME // deletes branch even if not merged with main branch

git fetch // Fetch all available remote branches (You won't be able to see all available branches in local)
git checkout BRANCH_NAME // it will show the selected branches