## 笔记
1. github 新建仓库，不要勾选创建readme选项
2. 在idea的terminal中执行以下命令
   ```$shell
    echo "# community-learn" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin git@github.com:haominglfs/community-learn.git
    git push -u origin master
   ```
3. 如果commit 后发现有问题，修改后，可以不增加新的commit,而是追加
   ```$shell
   git commit --amend --no-edit
   ```
