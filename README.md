# Atom关联github


1. Open your browser and log into your account on GitHub 
2. Click on the tab called "Repositories" 
3. Click on the button that says "New" 
4. Give your new repository a name, and then click "Create Repository". Don't worry about the other fields for now.
5. Copy第一个模块里面结尾是.git的 link。 

6. 打开终端：依次输入以下3行代码：每行结束按回车键

cd github

git remote add origin https://github.com/panzhang0628/livia_file.git （连接处放入第5步自己的链接）

git push -u origin master


然后输入github用户名密码
出现下面代码，说明成功。

Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 703 bytes | 351.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/panzhang0628/ChinaHouseClass05.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

7. 现在登陆github.atom.io/login
输入用户名密码
然后复制token的一系列字符串

8. 打开atom，右下角github, 输入用户名密码，
粘贴字符串。成功



