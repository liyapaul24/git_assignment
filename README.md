# Git Assignment - liyapaul24

a. What is an issue?  
It is a feature on Github that allows us to track requested changes and features in a software project.

b. What is a pull request?  
A pull request on GitHub is a feature that facilitates collaboration on a software project. It allows developers/users to submit their code changes for review, discuss the changes with team members, and, once approved, merge them into the main project.  

c. Describe the steps to open a pull request?  
Create a new branch for your changes. [git checkout -b assignemnt]  
Edit files and commit changes to the branch. [code README.md] [git add -A] [git commit -m "Description of the changes"]  
Push the branch to the remote repository. [git push]  
On GitHub, go to repository, click "New pull request," select branch, and compare it with the main branch.  
Add a title and description, then click "Create pull request."

d. Describe the steps to add a collaborator to a repository (share write permissions)  
Open repository on GitHub.  
Click on the "Settings" tab  
In the left sidebar, click "Collaborators"  
Click "Add people," enter their GitHub username or email, and select them.  
Click "Add [username]" to send the invite.  
By default, the new collaborator will have "Write" permissions, once they accept the invitation.  

e. What is the difference between git and GitHub?  
Git is a version control system, that allows to track changes and manage the code.  
GitHub is a web-based platform service for hosting and sharing that code online.

f. What does git diff do?  
git diff shows the differences between files or commits in Git repository, highlighting changes made to the code.

g. What is the main branch?  
The main branch is the primary branch in a Git repository where the stable code resides.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?  
It is better to create a new/seperate branch, add changes and create a pull request to merge changes to main branch.