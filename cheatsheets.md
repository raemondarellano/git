

To check your git repository

git remote -v   


######### To push your code in github #########

To check changes to your Local / Working directory
 
git status


To to add your change to your Local / Working directory

For all changes 

gid add .

for Specific file

git add my_file/

to add Tag to your Staging Directory (optional)

git tag -a v1.0 -m "my message"

To commit and create message before push

git commit -m "my first push"

To push your Staging diretory to your repository

git push origin master


To push tag to your repository (optional)

git push orgin master version_name



############ Creating branch, switch and delete branch ################

Creating Branch

git checkout -b new_branch

Switch other Branch

git checkout branch_name

Check Branch

git branch

Deleting branch

git branch -d branch_name


################ To check logs, Changes and tags ###############

To check commit logs

git log

To check edit changes to your local

git diff

To check tags

git tag 

git tag version_name


############## To delete your git file to your staging #################

To delete your git file in Staging directory

git rm  --cached my_file


########## To push your file to other branch ##########

To push your file to other branch (switch to other branch not updated, for example the latest code is staging and you want to update in production git switch production and then put the merge)

git merge branch_name

To push your updated merge

git push origin branch_name

######### Revert deleting file #############

To revert your deleting file in the Staging directory

git restore "file_name"
