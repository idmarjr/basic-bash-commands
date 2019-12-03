# Basic bash commands

In case you need any extra explanation about any command listed, I recommend you to go to [ExplainShell.com](explainshell.com).

## Where are you now (Print working directory)
`pwd`  

## List files/folders in the current directory
`ls`  
`ls -1` (Print vertical list)  
`ls -a` (Show all files, including hidden files)  
`ls -l` (Show list with extra information about each file/folder)

## Hard drive usage information
`df -h` (Show usage of all volumes in a human readable format)  
`df -h ~` (Show disk usage of your user folder)  
`df -h ~/Documents` (Shows disk usage of your user Document folder)  

## Clear viewport
`clear` (Clear your viewport without lose history by scrolling content to outside of visible area)  

## Manual of a command
`man pwd` (Show `pwd` manual)  
`man ls` (Show `ls` manual)
`man clear` (Show `clear` manual)
> In the manual view you can use keyboard arows to navigate throught the document.  
> To exit it, type `q`

## Change working directory
`cd folder` (change to folder named folder (if it exist))  
`cd folder/other-folder` (You can pass a path with more folders in order to save time)  
`cd ~` (Goes to your user directory)  
> Hit TAB while typing folder name will autocomplete it if theres a folder that matching name  

> Hit tab twice while typing folder name will suggest all folder names that match with the charactheres already typed  

## Create a new directory
`mkdir folder-name` (create a new folder called 'folder-name' in the current folder)  

## Create a new empty file
`touch file.txt` (Create a new file.txt with no content on it)  
> You can create a empty file of any extention that you like.

## History log
`history` (Display commands executed with the number of it in the history table)  
`!1` (Execute the command #1 from the history table)  
`!!` or  `!-1` (Exeute the last executed command)  
`!git` (Execute the most recent command from history table that start with _git_ keyword)  
`!?git` (Execute the most recent command from history table that contains _git_ keyword)  

## Open file
`open filename.txt` (Open `file.txt` using the default program of your system to open that particular extension)
