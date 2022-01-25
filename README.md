# jdH5
git checkout -b main
# 建立一个新的分支
git branch
# 查看当前存在的分支
git merge master 
# 将master分支合并到main分支上
git pull origin main --allow-unrelated-histories
# 加上后面这个选项允许不相关历史提交
git push origin main
# 将会push到main分支上，此项操作和网络原因有关系，失败后可以多尝试几次
git branch -D master
# 删除本地的master分支
git push origin --delete master
# 删除远程github仓库master分支，同样存在网络原因

## git pull –rebase origin master
## git init
## git add .
## git commit -m ""
## git remote add origin 仓库地址
## git pull --rebase origin main
## git push -u origin main
