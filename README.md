# Installing and using Git and GitHub on Ubuntu Linux: A beginner's guide

**Description:**
  
   GitHub, Inc. is an American multinational corporation that provides hosting for software development and version control using Git. It offers the distributed version control and source code management functionality of Git, plus its own features and GitHub is where over 50 million developers shape the future of software, together. Contribute to the open source community, manage your Git repositories.
    
1. **Installation of git in linux:**
    
> *sudo apt-get install git*

2. **Configuring GitHub:**

> *git config --global user.name "user_name"*

> *git config --global user.email "email_id"*

3. **Creating a local repository:**

> *git init Mytest*

where 'Mytest' is the new repository name.

> *cd Mytest*

4. **Creating a README file to describe the repository:**

> *gedit README.md*

Here readme.md file will creates on the current folder/path  & once text editor opens , enter data onto readme.md file.and also copy your code file onto the current working directory.
      
      
5. **Adding repository files to an index:**

Ex : we have 2 files which are "README.md" and "Temp.py" files,add it to the index by using the following 2 commands:

> *git add README.md*

> *git add Temp.py*

6. **Committing changes made to the index:**

> *git commit -m "some_message"*

"some_message" in the above command can be any simple message like "my first commit" or "edit in readme", etc.
      
7. **Create a repository on GitHub**

> Create a repository on GitHub. Notice that the name of the repository should be the same as the repository's on the local system. In this case, it will be "Mytest". To do this login to your account on https://github.com. Then click on the "plus(+)" symbol at the top right corner of the page and select "create new repository". Fill the details as shown in the image below and click on "create repository" button.

![new repository_creation](/new_repository.png)

Once this is created, we can push the contents of the local repository onto the GitHub repository in your profile. Connect to the repository on GitHub using the command:

Important Note: Make sure you replace 'user_name' and 'Mytest' in the path with your Github username and folder before running the command!
    
> *git remote add origin https://github.com/user_name/Mytest*

8. **Pushing files in local repository to GitHub repository:**

> *git push origin master*


## For more details , please have look on below file :

https://github.com/girishsj11/git_commands/blob/master/Git-Cheatsheet.pdf


## Adding/embed the video files into readme.md file :

> - [![**Wild Karnataka** documentary movie trailer]/(https://image.shutterstock.com/image-photo/crimson-backed-sunbird-leptocoma-minima-600w-1366963022.jpg)]/(https://youtu.be/QO79orOvYJA)
> - remove '/' from the beginning of image & video link address. 


[![Wild Karnataka documentary movie trailer](https://image.shutterstock.com/image-photo/crimson-backed-sunbird-leptocoma-minima-600w-1366963022.jpg)](https://youtu.be/QO79orOvYJA)
