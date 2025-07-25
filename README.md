GitHub Commands in git Session :

1. create the git repo in the github
2.  git config --list

3. to update username and pass : git config user.name 
	----> for chaging we can : git config user.name "XXXX"
	-----> then check your username : git config user.name 

4. For email adddress : git congif user.email "hjhjh@gmail.com"

5. git global and git local 

6. Untracked file : which says that git does'nt know about that 

7. git diff : can show the changes been added to the particular file 

8. git add : by this we can say to the git to add this file to the repo

9. git status : to check our file has been tracked or not 

10. git add . : to track all the files 

11. git commit -m : we can write the commit message with "-m" and it  just link the files with github 

12. git push : for adding it to the github branch.

13.git log --oneline : to simplyfy all the commands 

===========================================
 
HOW TO BRANCHING IN GITHUB

1. git checkout -b branch_name : ye btayega ki konsi branch pe move karna hai or kaha hai abhi 

============================
TO DELETE THE BANCH 

NOTE : do not in that branch which has to be deleted. 

1. git checkout branch_name 

2. git branch -d branch_name 

3. git remote -v : local repostiry git ke konse cloud se link hai 

4. git remote set url se kisi or ki url ko update kar sakte hai 

================================

TO PULL SOMETHING IN EXISTING BRANCH 

NOTE : If commit is not done then can't perform pull. 

1. git pull origin main   

2. git stash : matlab kuch usable junk jo git apne pas rkhega uska koi use nai h but rkhega need ke liye  

3. git stash apply stash_id : to check stash id 

4. git stash list : show all the list that has to be change 

5. git stash drop stash_id : it remove the id of the stash 

6. if apply and drop simultaneously :---> git stash pop stash_id

=============================
