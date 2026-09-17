# A02
This is the github repo for A02 
Xaidyn Lirano (xml) IS 117

---------------------------------------------------
Directions for Using Git, Github, and VS Code

**CREATE A GITHUB ACCOUNT**
1. You want to create an account on github.com
2. You want to use an email address (in this instance, use your school email), you want to create a user name, and a password you will remmeber
3. You want to simply follow the GUI directions (usually pretty easy questions) to complete the registration process
4. Once you're done doing that, you will be placed into your GitHub dasboard  
**CREATING YOUR FIRST REPO**
1. Within your dashbaord (on the left panel) you will see text that says "Top Repositories", you're going to click the green new button which is the button to create a new repo
2. You should now be prompted on the "Create a new Repository" page
    a. In the textbox "Repo name": Type your preferred name for your new repo
    b. In the textbox "Description": Type in a short description about your repo and what will be placed within it 
    c. Under the Configuration section, you will see Choose Visiblity: You can choose either Public or Private
    d. In the process you can also add a README file (just a good habit to have for future classes)  
**ENABLE HOSTING ON GIT REPO**
1. After you create your repo, you're going to want to enable hosting so you can see your webpages and code
2. You first direct yourself to the settings portion of the REPO where it says (Code, Issues, Pull Request...)
3. Click on settings and go down to the Pages tab. 
4. If you go to the Default Branch Section, you want to click on the main branch and confirm
5. Then you want to wait about a couple of seconds (15s) and refresh your page. You should see a link pop up to see the page on a web browser.  
**DOWNLOADING GITBASH**
1. You want to go ahead and search up Git Bash Windows install (or MacOS) just in case you have a Mac computer
2. You want to download the file and then run it
3. You can usually just click next on all of the settings in the GUI
4. Once you have it downloaded it you don't have to worry about it for now.  
**INSTALLING VSCode**
1. You can simply download this by searching up the name and downloading the file that corresponds to your copmuters OS. 
2. I would reccomend the basic settings (if there are any) and leaving IDE open for the next few steps  
**CONNECTING VSCode to GitHub via GitBash**
1. I would recommend making a folder for each repo. So go ahead and make a folder in your local computer
2. From there, in VSCode, you will see a button that says File. You want to click on that and click on open folder and open the folder you have just made
3. Now, in order to connect to Github from the browser within your VS Code, we need to do a couple of steps
    a. First you want to open your terminal in VSCode (You do that by going up to where you clicked the file button. Near that area there will be a terminal tab)
    b. Click on it and select new Terminal
    c. From there, you will see a terminal open, but you cannot write your git bash commands in this powershell terminal, we must change the terminal to GitBash
    d. When looking at the terminal you will see sections like "Problems, Output ..." I want you to look at the "+v" button and I want you to click on the down arrow
    e. From there you need to select Git Bash (and now we can start our GitBash commands to begin commiting things into GitHub)
    f. Now go back to GitHub to your repos dashboard. You will see this big green button called "Code" with this "v". You want to click on the more portion.
    g. Then you will see HTTPS highlights and a link to copy. Make sure you copy it and come back to VSCode
    h. Now in the terminal you want to type in "git clone PASTELINK". This will copy the repo within your local copmuter so you can start commtting things.
    i. Now start coding and creating some files  
  **COMITTING FILES FROM LOCAL COMPUTER TO GITHUB BROWSWER**  
1. Once your ready to commit, there are a few commands that you need to run in th terminal (make sure everything is saved)
2. "git status" is one of the first commands you'll run to see any changes in the files from the broswer and your local computer
2. Once you've confirmed, you must do "git add ." This will add all the files inside of the folder into the staging area for pushing into the repo
3. Next you want to run "git commit -m "MESSAGE" ". This is your commit message and should be named something that descibes the recent change you just made 
4. Once you do that, you want to do  "git push"
that should push your code into the GitHub browser. Make sure to refresh in the broswer to see the commit.

  **HEADS UP**  
If it's your first time, you may have to input your user and password into the terminal 
but the terminal will give you helpful commands to input into the terminal in order to do this!  

**Glossary**
- **Branch**: A Branch is a contained workplace that lets you work on different aspects of your program without affecting the main branch where finalized program code is placed
- **Clone**: Command that creates a copy of the repo in the browser within the local device (includes everything in the repo at the stage of clone)
- **Commit**: Stores changes from the staging area into the repo and simply helps track and manage steps of the project process 
- **Fetch**: Allows for the retrieval of the latest updates/downloads from a remote repo without the touching the local branch
- **GIT**: Version control system that helps track updates, allows for collaboration of multiple developers, and the act of restoring certain portions of code 
- **GitHub**: Web-based platform that incoorperates Git. It allows for version control, collaboration, and management within development projects
- **Merge**: Combines changes from diferent branches into a singular branch. Used primarily to intgrate branches (created for features testing) into the main branch
- **Merge Conflict**: Occurs when Git is not able to do any merges of branches due to conflicts like edits. Ex. multiple branches edit the same file or one branch deletes a file that another branch may have edited. 
- **Push**: Uploads commits to the remote repo where you can see changes occur in the repo. 
- **Pull**: Allows for developers to "pull" information and changes from the remote repo into the local repo.
- **Remote**: An environment (in this case) that is set on a cloud. Ex. GitHub is a cloud application
- **Repository**: A space on Github where developers can place files, source code, documentation, and othe important documents to a project. Allows for easy access to resources as well as simple collaboration. 