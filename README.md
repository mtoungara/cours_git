# cours_git
# Clone an existing repo from GitHub 
git clone https://github.com/mtoungara/cours_git.git

# Create a new local repo
git init my-new-repo

# Check status of changes in repo
git status 

# Stage files to commit
git add file1.txt file2.txt

# Commit changes with message
git commit -m "Updated feature X"

# Create a new branch
git branch new-feature

# Switch to another branch 
git checkout another-branch

# Merge new-feature branch into main
git checkout main
git merge new-feature
