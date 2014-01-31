#GET NEWEST / AND STAY UP TO DATE 

1. Git clone git clone git@github.com:<your-git-user>/WordPress.git

2. cd into WordPress folder and don't feel bad feeling Redundant since we're doing it! 

3. git remote add upstream https://github.com/WordPress/WordPress.git
Assigns the original repository to a var "upstream" 
4. git fetch upstream
# Pulls in changes not present in your local repository, without modifying your files
5. git merge upstream/master
# Merges any changes fetched into your working files
6. git push origin master
# Then push everything up to YOUR github repository

---




now mkdir myWordPress

cp -rv a b is the simplist solution I found where a would be wordpress source code and 

b would be yourApp

cd myWordPress

git init

go to github and add new repo called yourApp you can use this read me if you want

run these

git remote add origin git@github.com:<your-git-name>/myWordPress.git

git push -u origin master

You can just use this read me and even format it better if you'd like 


Make sure add the config file to to the gitignore
ie: 
/ wp-config.php 
Don't forget you'll need to rename that file to this.  I'll make this read better when I have more time but hopefully you'll have no worries..

