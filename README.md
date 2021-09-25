This is a testing project

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/zhujiannew/basic.git
git push -u origin master

git remote add origin https://github.com/zhujiannew/basic.git
git push -u origin master

add this file to ~/.ssh/config

Host github.com
User git 
Hostname ssh.github.com
PreferredAuthentications publickey
IdentityFile ~/.ssh/id_rsa
Port 443