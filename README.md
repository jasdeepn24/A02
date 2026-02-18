# A02


Directions:

The first step to getting started is downloading and installing **Git** from  https://git-scm.com/downloads. You should follow the installer prompts and leave the default settings as normal. Once it is installed, you can check if it worked by typing git --version into a new terminal window. 

Next you should download VSCode from https://code.visualstudio.com/, run the installer, and follow the setup wizard. VSCode is a code editor that works great with Git and **GitHub**. 

Next, you should head to https://github.com and click sign up to create your GitHub account. Make sure to enter your email, make a password, and choose a username. Then you should verify your email address. Then run two commands in the terminal to tell Git who you are. The two commands git config --global user.name "Your Name" and git config --global user.email "youremail@example.com" are able to link **commits** to you.

In VSCode, click the Accounts icon in the bottom left corner and select "Sign in with GitHub". This allows you to **push** and **pull** directly from the editor. 

In order to create a **repository** you should start by logging into GitHub, clicking the "+" sign in the top right, and select "New Repository". Name the repository, select it to be either private or public, check "Add a README file", and click create repository and the repo should be live. 

If you want to work on the repository locally you can **clone** it to your computer. When on your repo page you can click the green "Code" button and copy the URL. Then run this command, git clone https://github.com/username/repository-name.git, and it downloads the whole project to your machine and connects it to the **remote** repository on GitHub. 

After cloning, open the folder in VSCode by going to File->Open Folder and select the cloned repository folder. 

You can edit your files in VSCode and you will be able to see a blue badge show up on the Source Control Icon on the left sidebar showing how many files changed. After you are done editing the files you will need to stage and commit them. In VSCode you can click the Source Control Icon or press Ctrl+Shift+G / Cmd+Shift+G, then click the "+" sign next to files to stage them, type a commit message, and click the button to commit. You may also use the terminal commands git add . followed by git commit -m "Your commit message here". The messages should be short, clear and simple.

To upload your commits to GitHub, use push. In VSCode, click the "..." menu in Source Control and select "Push". OR in terminal you can use the command: git push origin main. To download the newest changes from the remote repository on GitHub, use pull. In VSCode, click the "..." and select "Pull". Or in the terminal use the command: git pull origin main. If you would like to see what changes exist on the remote without merging them automatically you can use **fetch**: git fetch origin. This downloads the changes but lets you look over them before merging. 

In terms of branches and merging, a **branch** is something that lets you work on a new feature without touching the main code. In VSCode, click the branch name in the bottom left corner and then "Create a new branch". Or you can use terminal by doing git checkout -b feature-branch-name.

When you are done working on a branch, you can switch back to main and **merge** your branch in. In VSCode, switch to the main branch, click branch name and select main, then click "..." go to "Branch" then "Merge Branch". Or in the terminal you can do git checkout main and git merge feature-branch-name.

You might experience a **merge conflict** which is when two branches change the same part of a file. VSCode will show the conflicts through colored areas of the code. You can click "Accept Current Change", "Accept Incoming Change", or "Accept Both Changes". You can also manually edit the file to keep whatever you want. There will be conflict markers throughout to help. You can remove the markers, save the file, stage it, and commit the resolved changes. 






Glossary: 

Branch - This is a separate copy of your code where you can work on new features without changing the main version.

Clone - Making a copy of a repository from GitHub to your computer so you can work on it locally.

Commit - This is like saving a snapshot of your changes with a message that describes what was done.

Fetch - Downloading updates from GitHub to see what was changed, but not adding them to your file yet.

GIT - Software that tracks every change you make to your files, and helps many people work together.

Github - A website where you can store code online and share it with others.

Merge - Combining changes from branch into another branch

Merge Conflict - When two people change the same line or part of the code differently and Git needs you to decide which version to keep.

Push - Uploading your saved changes from your computer to GitHub

Pull - Downloading the newest changes from GitHub and adding them to your local files

Remote - The online version of your repository stored on GitHub's servers

Repository - A folder that stores all of your project files and the history of all changes made to them.





References: 




