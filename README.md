# Deployment of Git and GitHub as Software Version Control + Proof of Concept (PoC), Process of Commit, Push, and Revert Code Changes

![picture with the words Cloud Project and icons for the services used](https://miro.medium.com/v2/resize:fit:720/format:webp/0*4pMzKNtf428_IFuB.jpg)

In this project based on a real-world scenario, I acted as a DevOps Engineer to migrate application and website code from a local repository
to remote repositories on GitHub.

My mission was to upload the code stored on my computer to GitHub, and validate the features between the repositories (local and remote) by running
some tests of code changes. Besides, to complete the validation process, I had to run a rollback procedure/reverting test, essential in
quick-response situations.

![picture with a graph showing the solution architecture](https://miro.medium.com/v2/resize:fit:720/format:webp/0*IQdpYZfbfEI1QdHO.jpg)

On my computer I’ve created a local folder and added the files from the website. In this folder I ran the command git init to start monitoring its contents 
and files. The git system works in two steps: first you have to prepare the files (Staging Area), so they can receive the commit on the next step, which 
acts as a confirmation (and archives it, in a certain way).

Next, I created a remote repository on GitHub, adding it to my local folder using the command git origin. The remote repository acts as a central depository 
for the files and changes, allowing multiple people to work on the same project in an asynchronous way. Git itself has tools to help you keep the local repository 
and remote repository synced. After making the commit, the user executes git push to send those changes to the remote repository. In the same way, the user uses git 
pull to receive the lasts changes from the remote repository, allowing devs to work with the latest changes available.

To practice these commands, I’ve made a change in the code directly from GitHub, and pulled those changes to my computer using git pull. I’ve made more changes and
executed a local commit. Git warned me that my machine had one more commit than the remote repository and instructed me to use git push to send the changes to the
remote repository and keep version parity. To train version rollback, I’ve utilized the last commit hash value to revert to the older version using git revert. 
All these changes, including the version revert, are registered and are easily accessible.

Git is one of the most simple and powerful tools available today and knowing to use it it’s essential for any I.T professional today, specially living in this
mega collaborative world we live in today.

