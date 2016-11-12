## Git创建新分支的方法
****
### 1. 创建新分支并推着到remote
```
	1. git branch devBranch1.xxx   // 新建本地分支

	2. git branch -a   // 查看所有的分支数据  （本地分支多了 devBranch1.xxx）

	3. git push origin devBranch1.xxx   // 把新分支 push 到远程服务器上

	4. git branch -a   // 查看所有的分支数据  （远程分支也多了 devBranch1.xxx）

	5. git checkout devBranch1.xxx    //  切换分支到 devBranch1.xxx 分支

	6. git branch --set-upstream-to=origin/devBranch1.xxx    devBranch1.xxx

```

**** 
### 2. 别的小伙伴的操作:
```
	1. git pull   // 拉取更新信息 （可以看到远程分支列表中多了  devBranch1.xxx）

	2. git checkout devBranch1.xxx   // 切换分支 
```


