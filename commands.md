# Basic Git Commands
mkdir get-for-devops             # Create a directory for the project
cd get-for-devops                # Change to project directory
git init                         # Initialize a new Git repository
pwd                              # Print working directory (where you are)
ls                               # List files in the directory

# Configuring Git User
git config --global user.name "shoaibi"                  # Set global username
git config --global user.email "shoaibcomputerscience@gmail.com"  # Set global email

# Working with Files
touch <filename>                  # Create a new file
vim <filename>                    # Open a file for editing in vim
cat <filename>                    # View contents of a file

# Branch Management
git branch                        # List all branches in the repository
git checkout -b dev               # Create a new branch called 'dev' and switch to it
git checkout dev                  # Switch to the existing 'dev' branch
git checkout main                 # Switch back to the 'main' branch

# Staging and Committing Changes
git add <filename>                # Stage a file for commit
git status                        # Check current status of the repository
git commit -m "commit message"    # Commit staged changes with a message

# Modifying Files and Checking History
git log                           # View commit history
git restore <filename>            # Restore the content of a file to the last commit
git rm --cached <filename>        # Remove file from the index (staging area)
rm <filename>                     # Delete a file from the directory

# Viewing Repository Information
git status                        # Check current status of the repository
git log                           # Show commit history
git diff                          # Compare changes between commits or the working directory




