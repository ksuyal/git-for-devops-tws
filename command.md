# Git Commands

### Initialize a new Git repository
git init

### Configure Git with your user email
git config user.email "kamal@gmail.com"

### Configure Git with your user name
git config user.name "kamal"

### Check the status of the repository
git status

### Add all files to staging
git add .

### Commit the changes with a message
git commit -m "all existing files are traced now"

### View the Git log
git log

### View the Git log in a single line format
git log --oneline

### Switch to the master branch
git checkout master

### Merge the `dev` branch into the `master` branch
git merge dev

### Push the changes to the remote `main` branch
git push origin main

### Fetch updates from the remote repository
git fetch remote origin

### Pull the latest changes from the `main` branch
git pull origin main

### Push changes to the remote `main` branch and set the upstream
git push -u origin main
