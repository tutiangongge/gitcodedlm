Git is a distributed version control system.git
Git is free software.hdjah
git 常用命令
git add 添加到暂存区
git commit -m "说明1"提交暂存区到分支

git status 获取当前状态

git reset --hard HEAD^/版本时间戳

git log 查看版本历史记录

git reflog  查看历史操作

查看区别  git diff HEAD -- filename 查看工作区文档与版本文件区别

git diff filename 查看最近文档修改内容


撤销更改
1.工作区更改
git checkout --  filename
2.撤销暂存区
git reset HEAD filename

删除
git checkout  用版本库里的版本替换工作区的版本
从版本库中删除该文件，那就用命令git rm删掉，并且git commit

git push origin master 上传代码
git clone https://github.com/tutiangongge/gitskills.git  从指定仓库克隆代码

git remote add origin git@github.com:michaelliao/learngit.git 关联本地仓库与远程仓库

git push -u origin master 加入u关联分支

