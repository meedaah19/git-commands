# git-commands
1. `git init`
Initializes a new Git repository in your project folder.

bash
git init

2. `git add README.md`
Add a readme file

bash
echo "# git-commands" >> README.md

3. `git clone`
Clone an existing file from my github

bash
git clone https://github.com/meedaah19/travel

4. `git add`
Add the new files added

bash
git add .

5. `git commit`
Commits the staged changes to the local repository with a message.

bash
git commit -m "Your commit message"

6. `git status`
To see if all file have been staged

bash
git status

7. `git branch`
To move the branch to main branch

bash
git  branch -M main

8. `git log`
Shows a history of commits

bash
git log

9. `git remote`
Adds a remote repository to your local repo.

bash
git remote add origin https://github.com/meedaah19/git-commands.git

10. `git push`
Uploads your commits to the remote repository.

bash
git push -u origin main

11. `git pull`
Fetches and integrates changes from the remote repository.

bash 
git pull origin main

12. `git branch`
Lists branches or creates a new one.

bash
 git branch (to list branches)

 git branch feature (creates a new one)


13. `git checkout`
Switches branches or restores files.

bash 
git checkout feature(restores files)

git checkout -b feature(Switches branches)

14. `git merge`
Merges another branch into your current one.

bash
git merge feature

15. `git revert`
Reverts a specific commit by creating a new commit.

bash 
git revert commit_id

16. `git reset`
Unstages files or resets commit history.

bash
git reset HEAD filename

17. `git rm`
Removes a file from the working directory and staging area.

bash 
git rm filename

