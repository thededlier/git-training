# git training
Make any changes you want to this repository. The aim of this repo is to let you experiment and get you comfortable with using the command line interface for git

## What is github?
Github is a platform where you can host your code repositories and manage your source code. This is useful in large teams where changes are being made by multiple people on same files.

## How to start ?
	* Open the git bash interface by right cicking in the folder you want to use and click git bash here
	* Now, if you have a proxy connection, set the proxy using the command 'git config --global http.proxy 172.16.0.2:8080'
	* Now clone the repo using the command 'git clone <URL of this repo>'
	* Once the clone is completed, make some changes to the folder, like adding new files and folders, changing code, etc
	* Once done, in the command line type 'git status' This will show the list of files in which changes have been made.
	* Now type 'git add .' to add all the changes. If you only want to add certain files then type 'git add ./file/path.css'
	* Now commit the changes by typing 'git commit -m "Write a description of the changes you made here"'
	* To push these changes online type 'git push origin master'
	* Note that during these stages, git may ask for your github login email and password

## Git basic commands

### Use the clone command to copy this repository to your machine.
```git 
git clone <URL of this repo>
```

### Try any command you want especially following commands and search on google to find more about them.
```git 
git pull -r origin master
```
```git 
git push origin master
```
```git 
git revert HEAD
```
```git 
git checkout master
git checkout <filename>
```
```git 
git reset HEAD <filename>
```
### Remeber to:

 * Change the proxy accordingly.
```git 
git config --global http.proxy 172.16.0.2:8080
```
```git 
git config --unset http.proxy
```
 * Google the commands you are not sure about.
 * Google the errors if you come across any.

##Resources for practicing git
 * https://try.github.io/levels/1/challenges/1
 * https://www.codecademy.com/learn/learn-git
 * http://gitimmersion.com/
 * http://rogerdudler.github.io/git-guide/