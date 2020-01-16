# 193B_Glucose_Monitor
# Using burn data
# Linking Local Folder to Remote Git Repo
Step 1: Create a folder to contain the repository

Step 2: Run
        
        cd to the folder directory

Step 3: Run

        git clone https://remote/repo/url

This command automatically links the cloned folder to the remote repo

Step 4: Run

        git remote -v
        
Use this line to verify linkage status
        
# Creating Your Own Branch
You can create your own branch in the repo locally by typing: 

        git branch <branch_name>
        
Then you can jump to your branch by running:

        git checkout <branch_name>

You can commit changes to your branch by running:

        git add .
        git commit -m "commit note"
        
You can push the branch back to the origin by: 
        
        git push origin <branch_name>
        
# 
