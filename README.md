# Git_introduction

```bash
# Configure Git (first time only)
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# Initialize a new repository OR clone an existing one
git init
# OR
git clone <repository_url>

# Check current status
git status

# Stage files
git add <file_name>        # Add specific file
git add .                  # Add all files

# Commit changes
git commit -m "Meaningful commit message"

# View commit history
git log

# Branch operations
git branch <branch_name>   # Create branch
git checkout <branch_name> # Switch branch
# OR
git switch <branch_name>

# Merge branches
git merge <branch_name>

# Push changes to remote
git push origin <branch_name>

# Pull latest changes from remote
git pull

# Discard changes
git checkout -- <file_name>
git reset --hard
