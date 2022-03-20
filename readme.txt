Git add  -A     将说有修改添加到暂存区            ###先提交到暂存区在提交到本地仓库  可以修改一部分在提交一部分 
Git add 文件名 添加单个文件到暂存区  
git  commit -m  "注释说明"
git log --stat      查看提交记录



######  放弃工作区的修改   git checkout filename


### 撤销commit 操作    Git  reset HEAD^1   

####分支相关

git checkout -b  新分支名字     以当前分支为之处新建分支 
Git  checkout main 切换分支名  