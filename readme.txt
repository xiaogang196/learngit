this is a test.
Git is a distributed version control system.
Git is free software.

mkdir 创建一个文件夹
pwd 显示当前目录
git init 把当前目录变成git可以管理的仓库
git add 添加文件到仓库
git commit -m文件提交到仓库
git status查看仓库当前的状态
git diff查看文件修改的内容
git log查看提交历史
git log --pretty=oneline缩减log日志信息
head 表示当前版本
head^表示上一版本
head^^表示上上一版本
head~100表示往上100个版本
git reset --hard head^ 回退到上一版本
git reflog 查看命令历史
git checkout -- file撤销工作区的修改内容
git reset head file 撤销修改暂存区的内容
git rm 删除一个文件
git remote add origin git@server-name:path/repo-name.git 关联一个远程库
git push -u origin master 第一次推送master分支的所有内容
git push origin master 