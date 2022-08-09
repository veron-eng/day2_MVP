# CHEAT SHEET DAY 2 - terminal and git 

# Terminal

pwd - print working directory, checks what directory you are in currently 

ls - lists all the files that are in the directory, this can be paired with a something
     called a flag like -l which gives more information about everything in the directory 

clear - removes the terminal work space and declutters everything, you can still look 
        at everything by scrolling up 

man - brings up a manual showing all possible commands if you type something like man ls
      it brings up all the flags that come up after it and its uses, a cool flag is -a  
      which brings up all the hidden files 

cd - brings you back to the root directory, can be couple with a dots after it: a 
     single dot . represents "here" and cd with 2 dots represents go up 1 level and 3
     dots represnts go up 2 

mkdir - makes a new directory 

touch - makes a new file, written in the format touch (filename).(extention)

open - can open a file using open (filename).(extention)

rm - removes a file, this cannot be undone, and does not work with directories but they 
     be removed using the flag -r, which means recursive 

mv - used to move a file, written as - mv (filename) (new place you are moving it to)
     mv is also used to rename files 

cp - used to copy a file that exists it is written using cp (filename) (new directory)
     can also copy a directory using flag -r


# GIT version control

git init - create a git repo by turning your directory into git repo

git status - see the status of whats hapening shows what needs to be added/ commited 

git add - to make git track the changes, after add insert . or the file name

git commit - to take a snapshot of the file added to the stage, has to be written as
             git commit -m "message" with the message describing what you did
        
git log - to see your history, use q to exit the log

git revert - to remove a commit from the log can be undone by adding the first 7
             numbers of the code after it 

            
# GIT-HUB 

can link the repo to the repository created on github using 

       git remote add origin (enter key from github)

everything can be pushed onto the github repo using:

        git push origin main 

git clone (ssh key)  - clones the repo

git pull - can update your cloned repo if someones updated it 

