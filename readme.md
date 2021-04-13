# ***GIT - A Distributed version control system***

---

## ***Version control system*** <br><br>
 Version control syste, (VCS) is a software that helps software devlopers to work together and make complete history of work.

 **Functin of VCS :-**
 - allow developers to work simultenously
 - Doesn't allow overwriting each others's changes.
 - Maintain a history of every version.

 **Functin of VCS :-**
 - Centralised version control system
 - Distributed version contral system

 Git is a Distributed version control system developed by Linus torwald.

---

## ***Important links for git*** <br><br>
 - [Official Git site](https://git-scm.com/)
 - [Git reference](http://gitref.org/)
 - [Book for Git](https://git-scm.com/book/en/v2)
 - [An Article for Git](https://codewords.recurse.com/issues/two/git-from-the-inside-out)
 - [Git for window users](https://wiki.spheredev.org/index.php/Git_for_the_lazy)

---

## ***Advantages of Git*** <br><br>
 - Free and open source
 - Fast and small
 - Implicit backup
 - Security
 - Easier branching

---

## ***Installation of Git and version check*** <br><br>
 - For Debian based Linux distribution
    - To Install Git
    ```terminal
    $ sudo apt-get install git
    ```
    - To check git version
    ```git
    $ git --version
    ```

    <br> 

 - For RPM based Linux Distribution
    - To Install Git
    ```terminal
    # yum -y install git-core
    ```
    - To check git version
    ```git
    # git --version
    ``` 
---

## ***Setting Username and email in Git***<br><br>
 - To add username in Git
    ```git
    $ git config --global user.name "your name"
    ```
    <br> 

 - To add Email in Git
    ```git
    $ git config --global user.email "example@mail.com"
    ```

---

## ***Git Commands***<br><br>
 - **Working with local Repositiries** <br><br>
    #
    - *git init* - Turn a directory into an empty git repositiries.
    ```git
    $ git init <Directory name>
    ```
    #

    - *git add* - Adds files in the staging area og git.
    ```git
    $ git add <file name>
    ```
    #

    - *git commit* - Record changes made to the file to a local repositiries.
    ```git
    $ git commit -m "commit message"
    ```
    #

    - *git status* - Show the current state of repositiries.
    ```git
    $ git status
    ```
    #

    - *git config* - To assign setting in git
    ```git
    $ git config <setting> <command>
    ```
    #

    - *git branch* - Perform an action on branch
    ```git
    # Create a branch
    $ git branch <branch name>


    # List all remote or local Branchs
    $ git branch -a


    # Delete a branch
    $ git branch -d <branch name>
    ```
    #

    - *git checkout* - To work on different branch
    ```git
    # checkout an existing branch name
    $ git checkout <branch name>


    # checkout and create a new branch
    $ git checkout -b <new branch name>
    ```
    #

    - *git merge* - Integrate Branchs together
    ```git
    $ git merge <branch name>
    ```
    #
    #


 - **Working with Remote Repositiries** <br><br> 

    #
    - *git remote* - to connect local repository with remote repository
    ```git
    # add remote repositories
    $ git remote <command> <remote name> <remote url>


    # list named remote repositories
    $ git remote -v
    ```
    #

    - *git clone* - To create a local working copy of an existing repository 
    ```git
    $ git clone <remote url>
    ```
    #

    - *git pull* - To get the latest version of a repository
    ```git
    $ git pull <branch name> <Remote url/name>
    ```
    #

    - *git push* - send local commits to the remote repository
    ```git
    # send local commits to the remote repositories
    $ git push <remote url/file name> <branch>

    
    # push all local branchs to remote directory
    $ git push -all
    ```
    

    #
    #


 - **Advance Git Commands** <br><br>

    #
    - *git stash* - To save changes made when they are not in a state to commit them to the repository
    ```git
    # Store current work untracked file
    $ git stash -u


    # Bring stashed file back to the working directory
    $ git stash pop
    ```
    #

    - *git log* - To show the chronological commit history for a repository
    ```git
    # Show intire file log
    $ git log


    # Show git logs with para meter
    $ git log --<after/before/since/untill>=<date>


    # Show git log based on author
    $ git log author="author name"
    ```
    #

    - *git rm* - Remove file or a directory from a working index(staging area)
    ```git
    # To remove file from the working index
    $ git rm --cached <file name>


    # To delete a file (forced)
    $ git rm -f <file name>

    
    # To delete a directory from the working index
    $ git rm -r --cached <directory name>


    # To delete a directory(forced)
    $ git rm -r -f <directory name>

    ```
    #

---

