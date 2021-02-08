# gdevs-portfolio

This website was created by the Generation Devs team and it highlights interesting facts about each member.

Technologies used includes:

* HTML5
* CSS3
* BOOTSTRAP

Members:
* Ilias
* Matthew
* Andy
* Kevin

GIT WORK FLOW

1. Go to main REPO and fork a copy

   https://github.com/generationdevs/G_Devs-Portfolio

2. Clone your forked copy onto your local machine

   git clone https://github.com/YOUR_GITHUB_USERNAME/G_Devs-Portfolio

3. Add main repo as a remote

   git remote add upstream https://github.com/generationdevs/G_Devs-Portfolio

4. Pull from the main repo with:

   git pull upstream main

5. When making code changes follow these steps

   0. git pull upstream main (To make sure your local copy main is up to date)

   1. git checkout -b Branch_Name (create new branch to work in never work in main branch)

   2. make required changes

   3. git add . or changed files (add files to staging area)

   4. git commit -m 'Commit_Message' (commit changes)

   5. when ready to push go back to main branch and run:

   git pull upstream main

   (grabs any changes made by others while your own changes were being made)

   6. go back to your Branch_Name and run:

   git merge main

   7. git push origin Branch_Name (push your changes on local machine to your forked copy)

   8. go to your forked copy of repo and start a pull request (make a request to merge changes with the main repo which should always be ready for deployment)
