# A03

This is a tutorial on setting up GitHub, Git, and Webstorm.

Table of Contents:
1. Creating an account on GitHub
2. Git download
3. Webstorm download
4. GitHub basics
5. Glossary
6. Resources

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
1. Creating an account on GitHub


- GitHub is a web-based interface that is useful for group work because it is open source and allows multiple people to work on the same project at the same time.
- Use the following link to navigate to the GitHub website to create an account: https://github.com/join
- You will need an email (business or school email recommended) to completely set up an account.
- After the account is made, click the icon in the upper right corner of the home page. There is a drop-down option labeled "Your Profile", use this to customize your account appearance snd information.


- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
2. Git download


- Git is a program used for the GitHub interface, and in order to use GitHub properly, it is recommended to download.
- In order to download Git, use the following link: https://git-scm.com/downloads
- Depending on the device being used (Windows, MacOS, Linux), click on the appropriate link, which will take you to the download page.
- At the top of the page it will state (I am using Windows so this might show slightly differently): "Click here to download the latest (2.35.1) 64-bit version of Git for Windows." This is the version that should be downloaded.
- After downloading, it will take you through the installation process. Once the process is finished, if you search "Git" on your computer, Git Bash, Git GUI, and Git CMD will show.
- Git can be accessed directly to commit and push changes made in an IDE such as Visual Studio or can be used by an IDE such as Webstorm to commit and push from there. If Git is being used directly, here is a cheatsheet of commands needed: https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html


- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
3. Webstorm download


Downloading Webstorm:
- Webstorm is a Jetbrains IDE used for making JavaScript easier. It is recommended to download this when working with GitHub and Git.
- In order to download Webstorm, use the following link: https://www.jetbrains.com/webstorm/download/#section=windows
- The website may try to charge you for a license to use the IDE, if you are a student it is recommended to make an account with your school email and information. If your university pays for Webstorm, you can get a license to use the services for free.
- Similar to Git, after downloading Webstorm it will take you through an installation process.


Connecting Webstorm with your GitHub account:
- In order to use Webstorm with your GitHub account, you need to register your account.
- Open the Webstorm IDE and press CTRL + ALT + S to open up the settings. Then press "Version Control" >> "GitHub". Click "Add Account" and this will lead you to a login page, and then an authorization page for linking your GitHub account with Webstorm.


Managing and working on your own GitHub projects with Webstorm:
- Create a new project (this can be found on the home screen or in the upper left corner).
- Looking at the navigation bar on the top of the project screen should be an option labeled "VCS". Click "VCS" >>"enable version control integration".
- Side note: you will need to be connected to your school's VPN or a VPN for this to work properly.
- After clicking "enable version control integration", click Git >> ok.
- Now the navigation bar on the top will be updated, check it again and click Git >> Manage remotes >> "+" (upper right corner of the manage remotes screen). Then copy and paste the URL of the GitHub repository link into the text-box shown.
- In the upper right corner of the project page is a blue arrow, this is used for updating the project. Click the arrow and the repository and branch information will be copied to the Webstorm project.
- Create a new file (not project), this will prompt the question "Do you want to add this file to Git?" Select "Yes".
- After making any changes, select the green check mark in the upper right corner to commit your work.
- Then click the green arrow in the upper right corner which will pull up a page, this will be used to push the changes. On the left will show all commits that haven't been pushed yet, they are automatically selected. Click "push" which will push the commit to GitHub, where you can then submit a pull-request there.


- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
4. GitHub basics


- Now that an account is created with GitHub, and Git and Webstorm are downloaded, what happens now? You are now able to start or join projects.

Making a repository:
- In order to start a project start on the home page of your GitHub account. By clicking the icon in the upper right corner (your profile image), click on a dropdown option labeled "Your Profile".
- Under the search bar there are a list of options: "Overview", "Repositories", "Projects", "Packages", "Stars". Click on "Repositories".
- On the right of the "Find a Repository" search bar is a green button labeled "New". Click this to start your first project.
- There is now the option to name your repository, as well as the option to set your project to private or public. Additionally, there is a checklist of pages that can be added, such as a README file and license. Specifically, the README file is used to give a short description of your project to teammates or viewers. This is useful to include.


Making a branch:
- After creating your repository, there will automatically be a main branch that will hold the code of your project. When you or teammates want to make edits to this branch, it is recommended to make a new branch off of the most recent version of the main branch (avoids conflict). This way multiple changes can be made at once, and they won't alter the main branch yet.
- In order to make a branch, after the project is created there will be a highlightable dropdown menu labeled "main" with a branch symbol. By clicking that dropdown, there is a text bar that states "Find or create a branch". Type the name of your branch, make sure it is branching off of the main one, and then click "create branch: [branch name] from [main branch name].


Commits
- After making changes to a branch, if you scroll to the bottom of a page there is an option to "commit" This will save any changes made. When submitting a commit it is important to give a description of the changes being made. An example of a good commit message would be: "Fix: Added tutorial on GitHub Basics". If you are editing lines of code it would be useful to include the line numbers of the lines changed.


- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
5. Glossary:


**Branch**: This acts as a parallel version and starts out as a copy of the main repository, allowing changes to be made without disrupting the original repository unless the branch is merged into it. This is useful for group work or work with many steps because multiple branches can be made for a project.

**Clone**: This is a command used to make a copy of every file, history, and branch from a  remotely existing project. This is done on a main computer or device instead of a server. The clone is still connected to the original, so changes can be pushed once finished (if the user is connected to the internet).

**Commit**:  Also referred to as a revision, this is a record of changes that are made to a branch or file. There is also a version history that shows who made the commit and what time it was made, alongside a description that explains the change made.

**Fetch**: This is a command used to add changes to a branch without the use of a commit. This is useful because it allows changes to be reviewed before they are committed.

**GIT**: An open-source program that is used to track changes made in text files, mainly being used by the GitHub interface.

**GitHub**: A web-based interface that is useful for group work because it is open source and allows multiple people to work on the same project at the same time. It is also useful for personal projects that require many separate parts and revisions.

**Merge**: This is a command that can combine work done on one branch of a project with another. It is usually done by using a pull request or request to merge.

**Merge Conflict**: This occurs when there is a difference between the branches trying to be merged. This is caused by different changes being made to the same line of a file, or when a user is editing a file that another user deleted. Merges can’t occur until all merge conflicts are resolved.

**Push**: This command is used to update a remote repository with locally made commits. To summarize, changes that are made by the user for a branch can be sent to the repository to update it.

**Pull**: This command is used for grabbing changes and merging them to a branch. This can be useful when multiple users are editing the same file and want to keep it updated.

**Remote**: Version of repository and branches that is hosted on a server. Local changes that are made on an IDE (and/or project clone) can be pushed directly to GitHub.

**Repository**: A project's main folder that holds all project files, and can include many collaborators.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
6. Resources:


- https://searchitoperations.techtarget.com/definition/GitHub
- https://docs.github.com/en/get-started/using-git/about-git
- https://docs.github.com/en/get-started/quickstart/github-glossary
- https://digital.gov/resources/an-introduction-github/#:~:text=GitHub%20is%20a%20web%2Dbased,and%20edit%20their%20site%20content
- https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches
- https://www.jetbrains.com/help/webstorm/github.html
- https://www.jetbrains.com/help/webstorm/manage-projects-hosted-on-github.html
- https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html


- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

