# git

1. git init
 
2. git config --global user.name "name"
 
3. git config --global user.email "emailId'
 
4. git status
 
5. git add --all (or) git add .
 
6. git status
 
7. git commit -m "message"
 
8. git log
 
9. git remote add origin GithubURL
 
10. git push origin BranchName
 
for creating branches:
----------------------
1. git checkout -b BranchName
 
2. git status
 
3. git add --all (or) git add .
 
4. git status
 
5. git commit -m "message"
 
6. git log
 
7. git push origin BranchName
 
Advance Commadns:
------------------
# Create a new branch
1. git branch <branch_name>
 
# List all remote or local branches
2. git branch -a
 
# Delete a branch
3. git branch -d <branch_name>
 
# Create a new branch
4. git branch new_feature
 
# List branches
5. git branch -a
 
# Delete a branch
6. git branch -d new_feature
 
# Checkout an existing branch
7. git checkout <branch_name>
 
# Checkout and create a new branch with that name
8. git checkout -b <new_branch>
 
# Store current work with untracked files
9. git stash -u
 
# Bring stashed work back to the working directory
10. git stash pop
 
# To remove a file from the working index (cached):
11. git rm --cached <file name>
 
# To delete a file (force):
12. git rm -f <file name>
 
# To remove an entire directory from the working index (cached):
13. git rm -r --cached <directory name>
 
# To delete an entire directory (force):
14. git rm -r -f <file name>
 
# if you change commit message
15. git commit --amend -m "message"
 
Logs View:
==========
# Display all logs
1. git log --all
 
#View n Most Recent Commits
2. git log -3
 
# Filter Commits By Author or Committer
3. git log --author <name>
4. git log --committer <name>
 
#Filter Commits by X Days Ago
5. git log --before <date>
6. git log --after <date>
 
exmple:
git log --after 2.days.ago
 
#Filter Commits by Date Range
7. git log --after <date> --before <date>
 
ex: git log --after "2014-02-01" --before "2014-02-02"
 
# View All Diff of Changes for Each Commit
8. git log -p
 
# View Summary of Changes for Each Commit
9. git log --stat
 
# View Just One Line Per Commit
10. git log --oneline
 
# View Commit History in ASCII Graph
11. git log --graph
 
# Format the Git Log Output
12. git log --pretty=format:"<options>"
 
ex: git log --pretty=format:"
