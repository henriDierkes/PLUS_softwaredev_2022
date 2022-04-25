# PLUS_softwaredev_2022
First steps in GitHub

Assignment 3 Info:

A new environment was created: 
   
   conda create --name new_env
    
To document the state of the environment and to allow others to install this environment on their computer, the environment was put into a requirements file with 
    conda env export --name new_env > requirements_henrike.yml

This file was then comitted and pushed to Github to make it available to others
   
    git add .. 
    git commit ..
    git push ..
 
The next task was to install a new environment based on a colleague's requirements file. 
First, a repo was forked and cloned to local disk. This was done by forking the repository in Github, copying the URL to that repository and typing it into the command line:
    
    git clone + URL
    
A new environment was then created from this request file:
    conda env create --file envname.yml
    
New packages that were not already in the environment were installed:
    
    conda install leaflet
    conda install sphinx
 
 Again, the changes were committed and pushed to GitHub and a pull request was created to merge the changes into the Collegeaus repository. 
    
