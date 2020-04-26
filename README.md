# Steps to connect R files with git

### In git hub:
- create a new repository R-git-learn
- clone the address


### In R terminal:
- create a local directory: mkdir R-git-learn
- cd R-git-learn
- git init
- echo "Steps to connect R files with git" > README.md
- git add -A
- git commit -m "add first commit"
- git remote add origin https://github.com/xc308/R-git-learn.git   *to connect local repo with the remote one on github*
- git push -u origin master    *to first push all local commits to remote repo and set up a remote master branch*


### In R studio:
- File - new repository - version control - copy the github address - set subdirectory on local

### Thinking:
- with the initialization in R terminal, the file - version control is the same as the above steps, so might be a redundant. 

- is it possible to run different versions of simulations on different branches on different laptops simultaneously?



### Let's try on another laptop

- log in git hub on another laptop
- clone the adress
- on local terminal git clone address
- open the README.md file in the **Files** in the lower right-hand panel
- git checkout -b update2
- make some changes for the md file
- git add; git commit; git push origin update 2



### Time to finish the project on coursera
1. finish the one project
2. finish peer review
3. skip the cloud computing part -- sorry no certificate then


### (Additional section) 
![a pic](https://github.com/xc308/R-git-learn/blob/update/image/屏幕快照%202019-12-29%2020.29.06.png "This is a pic took in Cambridge)

<img scr=https://github.com/xc308/R-git-learn/blob/update/image/屏幕快照%202019-12-29%2020.29.06.png alt="This is a pic took in Cambridge" width="400" height="800">
