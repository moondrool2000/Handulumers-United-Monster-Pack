# Git Basics (Linux)
You can click through the website's UI and save yourself all the authentication trouble if you want.  It will do the same things as the commands below.

* note I use <word> to denote something the user needs to fill out.  Do not include the brackets in your actual command.

Get any new changes from github.com  
`git pull`  
* always run this before trying to push.  Honestly, life is easier if you run it between commits and just all the time too.  

Add a file that you've changed/created.  
`git add <filename>`  
* you can put . as the filename to add all files in the current directory  

Commit your changes  
`git commit -m "<short description of your changes>"`  

Send your changes to github.com  
`git push`  
* there's a hundred and one ways to authenticate with github.  Choose what makes sense for you.  
* moondrool2000 will have to give you permission to push directly  

Check if you need to add or commit files  
`git status`  

See what you changed about file(s)  
`git diff <optional filename/directory>`  
