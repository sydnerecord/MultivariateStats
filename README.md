# University of Maine WLE650-0002 Graduate Seminar in Wildlife Science:Multivariate Statistics

## Files
This repository contains .Rmd files for Lab Assignments. Students may access the code associated with this repository in a number of ways depending on their familiarity with Github. Github instructions adapted from Macrosystems Eddie (https://zenodo.org/doi/10.5281/zenodo.10380339).

### Option 1: Download code directly (easiest option)

1. Click on the .Rmd file of the lab code you want to access. 
2. This will take you to a new page that shows the code. Click on the down arrow in the bar above the code to download the .Rmd file directly, which you will be able to open in RStudio.

### Option 2. Option 2: Create an R Project (advanced option)
1. If you don't already have one, make a GitHub account.
2. Near the top of the repository page, click the "Fork" button to create your own copy of the module code repository in your GitHub account.
3. Open RStudio on your computer.
4. In the top right corner, click the "Project: (None)" button.
5. In the dropdown menu, click "New Project".
6. Select "Version Control".
7. Select "Git".
8. Go back to your internet browser. To retrieve the URL for this code repository, click the green "Code" button near the top of the repository page and copy the HTTPS link in the dropdown menu.
9. Go back to RStudio. Paste the link into the "Repository URL" box. Type a name for your project into the "Project directory name" box. Select where you would like the project to be located on your computer in the "Create project as a subdirectory of" box.
10. Click "Create project".
11. RStudio should create a project which allows you to access and manipulate files locally.

### Option 3: GitHub Desktop
This is my personal preference that creates an interface with GitHub similar to the File Explorer on Windows or the Finder on a Mac. GitHub Desktop is available for download [here](https://desktop.github.com/).

### Committing and pushing changes back to GitHub
The advantage of accessing the module as an RProject via GitHub is that you now have version control, which means you can track (and revert if needed) your changes over time. You also have a copy of the project stored remotely (on GitHub) as a backup if your computer is lost or broken. However, in order to benefit from these advantages, you will need to commit and push any changes you make to the module files locally on your computer back to GitHub. To do this from RStudio:

1. Navigate to the "Git" pane in the top right panel of RStudio.
2. Click the check box next to each file you have changed.
3. Click "Commit".
4. In the top right corner of the pop-up window, type a brief but informative note to your future self documenting the changes you have made.
5. Under your message, click "Commit".
6. Once the changes are committed, click "Push".
7. RStudio will ask for your GitHub credentials to verify that you have rights to push changes to the remote code repository. Enter the email you used to create your GitHub account under 'username' as well as your GitHub token under 'password', then push your changes. Instructions for obtaining a token can be found [here](https://docs.github.com/en/enterprise-server@3.9/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens).