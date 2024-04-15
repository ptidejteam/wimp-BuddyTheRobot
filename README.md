# buddytherobot
Repository for Blue Fog Buddy Robot


## Steps to add submodules
### Step 1: Clone the Main Repository 
```
git clone https://github.com/your-username/main-repo.git
cd main-repo
```
### Step 2: Add the Submodule
To add a submodule, use the git submodule add command. Replace other-username and submodule-repo with the submodule's GitHub username and repository name. Also, specify a path where you want the submodule to be placed within your main repository.
```
git submodule add https://github.com/other-username/submodule-repo.git path/to/submodule
```
### Step 3: Commit the Changes
After adding the submodule, you need to commit the changes to your local repository.
```
git commit -m "Add submodule-repo as a submodule at path/to/submodule"
```
### Step 4: Push the Changes to GitHub
Finally, push your changes to GitHub:
```
git push origin main
```
