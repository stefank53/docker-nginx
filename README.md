# Create a new repository on the command line
 
echo > README.md  
git init  
git add README.md  
git commit -m "first commit"  
git remote add origin https://github.com/stefank53/docker-nginx.git  
git push -u origin master  
 
# Push an existing repository from the command line
 
git remote add origin https://github.com/stefank53/docker-nginx.git  
git push -u origin master  

# Pull from GitHub and force overwrite of local files

git fetch origin main  
git reset --hard origin/main  
git pull  
