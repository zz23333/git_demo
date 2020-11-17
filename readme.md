# git 学习笔记


   

## git 配置

    1. git config --global user.name "duhaipeng"
    2. git config --global user.email "duhaipeng@enn.cn" 

## git 语法
    1. git init : 初始化本地仓库
    2. git add <file> : 添加本地文件到暂存区
    3. git commit -m <message>： 暂存区文件提交到本地仓库
    4. git status : 查看当前状态
    5. git log / git log --pretty=oneline : 查看提交日志
    6. git reset --hard HEAD^ : 回退到上一版本
       git reglog: 查看命令历史
       git reset --hard <commit_id>： 回退到指定版本
    7. git checkout -- <file> ： 丢弃工作区的修改,把文件回退到最后一次的状态，git commit 或git add
       git checkout: 版本库里的版本替换工作区的版本，无论工作区是修改还是删除，都可以“一键还原” 
    8. git reset HEAD <file> : 丢弃暂存区的文件
    
    
## 远程仓库
    1. git remote add origin <git repository url>: 其中origin为远程库的名字
    2. 