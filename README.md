# TestCar
# 第一步：先登陆github 创建一个仓库;
#在本地创建一个仓库的目录
#第二步：初始化当前目录 git init

#第三部：配置用户名密码：（用来访问git服务器的）

#$ git config --global user.name "youname"
#$ git config --global user.email "youeamil@email.com"

#查看当前用户名和邮箱
#$ git config user.name

#$ git config user.email


#第四部：生成本地计算机访问git服务器的密钥(key)

#$ ssh-keygen -t rsa -C "你的邮箱"

#然后一直回车

#第五步：使用git clone ssh的url来将服务器的工程拷贝下来

#遇到问题  windows访问id_rsa权限问题

#$ chmod 600 ~/.ssh/id_rsa 

#已使用上述命令解决

#使用ls命令查看子目录

#cd 子目录名进入到master分支

#提交命令--------------->>>>>



git status  -----打印当前项目里所做的修改


git add 文件名 ----将文件加入到缓存区

git status  -----打印当前项目里所做的修改

add 成功后再次打印当前的 文件名会变色

git commit -m "描述"  ---将文件提交到缓存区

git status  -----打印当前项目里所做的修改


git push origin master --将修改推送到服务器
