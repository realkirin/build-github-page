# mkdir project-name
# cd project-name
# git init
# touch index.html
# git add index.html
# git commit -m "first commit"

for https
# git remote add origin https://github.com/realkirin/build-github-page.git

for ssh
# git remote add origin git@github.com:realkirin/build-github-page.git

change remote
# git remote set-url origin git@github.com:realkirin/build-github-page.git
link:
https://help.github.com/en/articles/changing-a-remotes-url

# git push -u origin master


# -u
# origin只是一個別名


產生ssh key
# ssh-keygen -t rsa -C "your_email@example.com"
# 會在 ~/.ssh/ 下產生 id_rsa 及 id_rsa.pub(公鑰 貼到github setting)

# ssh-agent -s
# ssh-add ~/.ssh/id_rsa


測試連線
# ssh -T git@github.com