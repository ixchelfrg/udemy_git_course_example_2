README.md

## to create a new repository on the command line

echo "# udemy_git_course_example_2" >> README.md <br>
git init <br>
git add README.md <br>
git commit -m "first commit" <br>
git remote add origin url <br>
git push -u origin master <br><br>

## push an existing repository from the command line

git remote add origin url <br>
git push -u origin master <br>

## video steps

git clone url optional argument (directory name) <br>
git status <br>
git add README.md <br>
git commit -m "Inital commit." <br>
git push origin master <br>

## note

After I did "git clone url" since I already had README.md in folder that I cloned repo on, it already pushed the file there. 

## to check git version

git --version

## terminal commands

<b> pwd: </b> tells you where you are <br>
<b> mkdir directory name: </b> make a new directory<br>
<b> cd directory name: </b> change directory to specified directory <br>
<b> ls -la: </b> to see what is in the folder
<b> ctrl + l: </b> to clean output in terminal window

## more git commands

<b> git diff README.md  : </b> tells you the differences made to file, what was added or removed <br>
<b> git log : </b> lists commits w/ID, time stamp & email <br>
<b> git checkout file name : </b> after make changes to file & save, this command will allow you to checkout or see file before the change was made



## note

Do not have to do each time "git push origin master" can just do "git push".

## more terminology

<b> (origin/master) : </b> where github is currently at <br>
<b> (HEAD -> master) : </b> where we currently are at

## to recover previos commited file

<b> git checkout #ID : </b> copy ID # from commit that you want, when you do this it will then say <b> HEAD is now at "commit" </b><br>
<b> git checkout master: </b> will take you back to branch master.


