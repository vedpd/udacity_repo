# udacity_repo
This repo is for the practice and regular assignments from Udacity MLOps nanodegree

Here are the commands towork on git:-
1. git clone "url_git_repo" : This command is used to clone a repository which publically accessible.

2. Post cloning : do check for the directory and then change the local directory to cloned directory.

3. Touch "file_name.extension" : To create a new file from terminal

4. Nano "filename" / vi "filename" : to edit the file. 
		    In case of vi ( type i to get into insert mode, press esc, 
		    then w to save it and q to quit) 

5. git add "filename" or git add * : to add files to git pipeline or staging area.

6. git commit -m "comments" : this is to commit the files to the git repo from staging area
		            Note: files have been added to separate branch created internally.
			    These files would need to get moved to main branch to appear on repo.

7. git push : This command would finally move the file which was committed to main branch as change.

8. git status : This command helps to check if:-
		a. existing differences with cloned repo on local vs available online.
	        b. any non committed files
		c. if git commit has been done or not and file is showing in the git pipeline or not. 

9. git checkout -b "branch_name" : to create a new branch with branch name and switch to that branch. 

10. git checkout <branch_name> : to move to a new branch from current branch. 
				This command allows you to move from one branch to another when you are not also looking to create the branch.

11. git branch : lists all the branches presently in git and which one is active. 

12. git branch -d <branch_name> : to delete any git branch. (Note : you shouldn't be running/active the branch which is going to be deleted).

13. git merge :this is used to merge the branches/ code
