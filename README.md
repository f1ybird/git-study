# git-study222

测试拉取远程代码：git pull --rebase

1、拉取远程代码：git pull --rebase

     作用：相当于执行git fetch origin & git rebase origin/master，比直接git pull代码的分支线路图更整洁清晰，不会出现交叉线。相当于代码是在远程代码的基础上修改。

     废弃：git pull，这个操作相当于git fetch origin & git merge origin/master，形成冲突后，分支线会形成交叉。不再建议使用这种。
222
444
