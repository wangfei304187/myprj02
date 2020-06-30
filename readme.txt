
$ git add readme.txt
$ git commit -m ""

git log
git log --pretty=oneline
git reflog

git reset --hard HEAD
git reset --heard HEAD~1

git diff HEAD -- readme.txt

第一次修改 -> git add -> 第二次修改 -> git add -> git commit

[撤销 - 丢弃工作区的修改]
git checkout -- readme.txt


[删除文件]
$ git rm test.txt
$ git commit -m "remove test.txt"


git remote add origin https://github.com/wangfei304187/myprj02.git
git push -u origin master


git clone https://github.com/wangfei304187/myprj02.git



[branch]
git checkout -b dev     or     git switch -c dev
git branch
git checkout master     or     git switch master
git branch
git checkout dev        or     git switch dev
git branch

git checkout -b bugFix af66f0
git branch -d bugFix

git branch -D newFeature


[merge]
git checkout master
git merge dev
git branch -d dev


[stash]
git stash
git stash list
git stash apply stash@{0}




===========================
…or create a new repository on the command line
echo "# myprj02" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/wangfei304187/myprj02.git
git push -u origin master
                
…or push an existing repository from the command line
git remote add origin https://github.com/wangfei304187/myprj02.git
git push -u origin master
===========================



