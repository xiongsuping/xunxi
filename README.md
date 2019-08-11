## 学习

### 轮播    

 - 1、三位置轮播
    
 - 2、呼吸轮播

第一步 克隆远程，建立本地与远程仓库的链接
git clone https://github.com/xiongsuping/xunxi.git

第二步 查看本地更改文件状态（与远程仓库的比对状态）
git status

第三步 提交更改及新增文件
git add .  // 表示提交所有文件（更改或新增的）
git add <文件名> //表示提交该文件更改

第四步 提交本次更改的文件描述
git commit -m "文件描述"

第五步 将本次更改提交到远程仓库
git push origin master  // origin 表示提交的仓库分支

其他
git remote -v //查看分支状态 origin ==> https://github.com/xiongsuping/xunxi.git

git remote add xsp https://github.com/xiongsuping/xunxi.git //增加分支地址映射

git remote remove xsp //删除xsp映射分支



