1.  **Download and Install Git Bash**: First, download and install Git Bash from the official Git website. Follow the installation instructions provided.
    
2.  **Open Git Bash**: Open Git Bash by double-clicking on the icon that appears on your desktop or by searching for Git Bash in the search bar.
    
3.  **Create a New Folder**: Create a new folder on your local computer where you want to store your files. You can do this by right-clicking anywhere on your desktop or in a file explorer window and selecting "New Folder."
    
4.  **Navigate to the New Folder**: Navigate to the new folder by typing the following command into Git Bash:
    
    bashCopy code
    
```bash
cd /path/to/folder
```


    Replace "/path/to/folder" with the path to your new folder.
    
5.  **Initialize Git**: Initialize Git in your new folder by typing the following command into Git Bash:

    `git init`
    
6.  **Create a New Repository on Github**: Go to Github.com and log in to your account. Click on the "+" sign in the top right corner and select "New repository." Give your repository a name and description, and make sure it is set to public or private as desired. Then click "Create repository."
    
7.  **Copy the Repository URL**: Once the repository is created, copy the repository URL provided.
    
8.  **Connect Local Repository to Github Repository**: In Git Bash, type the following command to connect your local repository to the Github repository:
    
    csharpCopy code
    
    `git remote add origin <repository URL>`
    
    Replace `"<repository URL>"` with the URL you copied in step 7.
    
9.  **Add Files to Local Repository**: Add the files you want to upload to your repository to your local repository. You can do this by dragging and dropping the files into the new folder or by using Git Bash commands to create and edit files.
    
10.  **Commit Changes**: Once your files are added, commit the changes to your local repository by typing the following command into Git Bash:

    `git commit -m "First commit"`
    
Replace "First commit" with a brief description of the changes you made.
    
11.  **Push Changes to Github**: Finally, push the changes to your Github repository by typing the following command into Git Bash:
    
    `git push -u origin master`
    
This will upload your local files to your Github repository.