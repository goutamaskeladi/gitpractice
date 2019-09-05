# gitpractice
A simple demo repository to show basic Git workflow.

# what is git? 
Distributed Version Control System

# why version control?
Backup/Archive, Versioning/History, Undo Changes, Comparing, Collaboration/Teamwork, Blame/Learning Moment, Isolation of Changes, Code Review.

# types
Two main types - Centralized, Decentralized/Distributed.
* Centralized - Subversion, CVS - Requires connection to central server for most operations.
* Distributed - Git - Most operations are local. Central server not required. Later push the commits made on your local branch to a remote repository.

# commonly used git commands

  * To check the git version, 
  
        - git version

  * To set git config,

        - git config --global user.name "<Your name>"
        - git config --global user.email "<Your email>"
        - git config --global --list 

  * To clone existing repository from github,
  
        - git clone <github-repository-path>

  * To check the status,
  
        - git status
  
  * To add files into staging area,
  
        - git add <filename> or to add all files git add .
 
  * To commit to the local repository,
  
        - git commit -m "<enter-the-description>"
  
  * To add an existing local repository into remote repository,
  
        - git remote add origin <github-repo-url>
 
  * To push remote repository, 
  
        - git push origin <branch>
 
  * To check git config,

        - git config --global --list

  * To initialize empty git repository,

        - git init or git init <repository-name>

  * To see all kinds of files and folders(linux command),

        - ls -al

  * To add README.md file,

        - git add README.md

  * To update the local repository,

        - git pull origin <branch-name>

  * To unstage a file,

        - git rm --cached <file-name> i.e git rm --cached README.md

  * To remove the .git file(linux command),

        - rm -rf .git
 
  * To remove file and directory(linux command),

        - rm <file-name> or rmdir <folder-name>

  * To add and commit process into one step,

        - git commit -am "<enter-the-description>"

  * To check the list of branches present in the repository,

        - git branch

  * To create a new branch,

        - git branch <branch-name> i.e git branch development
 
  * To delete a branch,

        - git branch -d <branch-name> i.e git branch -d development
 
  * To show git log in one line,
  
        - git log --oneline

  * To merge the branch,
    
        - git merge <branch-name> i.e git merge development

  * To abort the merge,

        - git merge --abort

  * To create a new branch and switch to it,

        - git checkout -b <branch-name> i.e git checkout -b feature

  * To merge master contents in feature branch and to condense merge in one line,

        - git merge <branch-name> <branch-name> i.e git merge feature master

  * To open the files from command prompt,

        - start <file-name> i.e start README.md

  * To check the difference use,
   
        - git diff  (type q to quit)

  * To rebase,

        -  git checkout <branch-name> i.e git checkout feature

        -  git rebase master

        -  git merge feature

   * To abort rebase,

         - git rebase --abort

   * To stash,

         - git stash

         - git stash list

         - git stash apply

   * To Tagging,

         - git tag

         - git tag -a v1.4 -m "My version 1.4"

         - git tag v1.4

         - git show v1.4

         - git tag -a v1.2 9fcebo2

         - git push origin --tags

         - git tag -d v1.4
        
   * To change git config edit ~/.gitconfig i.e vim ~/.gitconfig

   * To ignore unwanted files and folders: .gitignore
         
            Specific File: MyFile.ext
            File Pattern: *.ext or *.log
            Folder: my-folder/ or log/
 
   * To alias,

         - git log --all --graph --decorate --oneline

         - git config --global alias.hist "log --all --graph --decorate --oneline" 

         - git hist

    * To revert,

         - git revert HEAD  

         - git checkout <commit-id>

      

    

   

      

     

    
