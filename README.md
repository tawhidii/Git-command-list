## All Commands

### Regular commands:
* git init // initialize local git repositroy 
* git add index.html // add 'index.html 'file to index
* git add . // add all files to index
* git status // check status of working tree
* git commit -m 'messages' // commit changes in index
* git push // push to remote repo
* git pull // pull latest from remote repo
* git clone // clone repository into a local new directory



* cd New Folder // New Folder is a local repo	
* git init // into the New Folder repo. now need to connect with online repo 
* git remote add origin ..link..of..online..GitHub..repo.. // linking between New Folder & repo 
* git push -u origin master // pushed codes from New Folder to Online repo
* git pull origin master
* git commit -m 'Another File Added' another.js // individual messages for individual files

* git branch new // creating another branch named 'new'
* git checkout new // switching into the 'new' branch
* git checkout master // before merging, selecting the root branch
* git merge new // merged 'new' branch with 'master' branch

* git rm --cached index.html // unstage
* git add *.html // stage again   

* git remote // for displaying origin
* git remote -v // for displaying individual links of origins
* git show // for showing the details modifications into the code

* git commit // Starts Vim Editor // Press i then 
* Press Esc, Then Press :wq // For Backing into git bash 

* touch index.html // Creating New Files into the Local Directory
* touch .gitignore //For Ignoring Specific Files    

* git config --global user.name 'Khademul Bari' // Declaring Global Name
* git config --global user.email 'barii.py@gmail.com' // Declaring Email

### If your Local branch and remote branch is the same name then you can just do it:
* git push origin branchName

### When your local and remote branch name is different then you can just do it:
* git push origin localBranchName:remoteBranchName

### 1. Create New Repo > Clone the Repo to the Local Git Folder > Copy Source Code to the Local Git Folder:
* git clone Repo Link

### 2. Repo Folder > git bash here > then give those commands:

* git status
* git add .
* git status
* git commit -m "Add The File"
* git push -u origin master

