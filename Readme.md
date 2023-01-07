read me...

steps: 
1. first you will create a repo on github called "myrepo"

2. now you will crete a folder ➡️ github on your system
3. run git init commit in this folder
4. add Readme.md file in this folder
5. now run git add Readme.md
6. commit this newly added file as "first commit"
7. now run git add origin command (provided on gitHub, copy it and paste)

now after adding git origin you need to run one more command that is to verify your username and useremail..

so,
8. git config --global user.name ""
9. git config --global user.email ""

now in order to push the commit's on remote which you have done on your local system, we use 

10. git push -u origin master


# adding changed files to the remote

now let suppose you have added few more text to this file, and you want to see this changes on your remote.

1. git status 👉 to see the changes
2. git add "file name"
3. git commit -m "...."
4. git push -u origin master


and hence we repeat the above procedure to push anything on your remote..😃

any changes 
