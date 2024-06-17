# check
nk's checking
This is my first git change and commit


# Working of Git

- 1) git clone "https://github.com/<username>/<repo_name>.git"
    - This clones the remote repository on your local machine, 
    - you can now, cd into that directory
    - and can now modify curent files or, add new files (on local level/your laptop/machine)
- 2) git status
    - This will tell you that you have some modified, or newly added files
    - but they are untracked
    - you need them to be tracked, hence next command
- 3) git add <modified_file_name>/<newly_added_file_name>
    - This will now enable git to track the modified or added file
- 4) git commit -m "<message>"
    - This will commit the tracked changes in the local git repository
    - on the current branch of the repository
    - if you want these changes to be reflected on the remote branch, you will need the next command
- 5) git push
    - This will push the commited changes to the remote repository
    