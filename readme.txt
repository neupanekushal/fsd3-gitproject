commands:
git --version: to check git version

git init
git status: 
git add .

now the commiting part:

git commit -m 'here attach something for you to know what was the purpose of commiting' styles.css
eg:
git commit -m 'initial commit' .

git log -- shows the description of previous commits. gives every thing we did so far


git checkout branchname: change from one branch to another.
   in theis case we change to master branch

git branch : check the current branch
git branch branchname : to create the new branch

to connect our project in visualstudio and  git cloud:
git remote add origin https://github.com/neupanekushal/fsd3-gitproject.git

to push master branch to the git hub:
git push -u origin master


