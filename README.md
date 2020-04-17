# web0

git: a piece of software used for version control

version control is a helpful tool to restore, test, work on codes together and merge codes etc. 

github is a central storage place. 

<!-- # assuming the following is done in GNU bash/command terminal -->

git clone <url> copy a diretory to whatever you are using
<!-- git clone https://github.com/frankczw/cs50_web_lec0 -->

cd: change directory
<!-- cd cs50_web_lec0/ -->

ls: list all files (in the directory)

touch: creates a new files
<!-- touch hello.html \create a HTML file in the directory -->

git add <file name> adds the file into the repository 
<!-- git add hello.html --> 
<!-- hello.html is the file that I want to track -->
<!-- git add * \adds everything>

git commit -m "message"
<!-- git commit -m "added hello.html"; -m means add message, and message are notes to add for the changes-->
git status: tells us the current status of the repository

git push: pushes the changes to the repository

git pull: download the latest version FROM the repository

git log: shows the history of the stuff

git reset --hard <commit> <!-- reset to commit version -->
git reset --hard origin/master <!-- reset to repository (clone) version -->

right click on a web page, view page source will show the html content of the page

