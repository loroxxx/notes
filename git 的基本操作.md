###关联电脑
1. $ ssh-keygen -t rsa -C "youremail@example.com" ，不需要设置密码
2. 登陆GitHub，打开“Account settings”，“SSH Keys”页面：点“Add SSH Key”，填上任意Title，在Key文本框里粘贴id_rsa.pub文件的内容


###简单操作：本地初始化一个新仓库，新增文件并提交

1. git init
2. git add README.md
3. git commit -m "first commit"
4. git remote add origin https://github.com/loroxxx/notes.git
5. git push -u origin master

###简单命令

*查看文件状态 git status