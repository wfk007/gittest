1. git rm --cached fileName

   移除 git add 暂存区内容

2. git branch a 

   新建分支 a

3. git checkout a 

   切换到 a 分支上

4. git checkout -b a 

   新建 a 分支并自动切换到分支 a

5. git branch -d a 

   删除 a 分支，如果 a 分支还未和 master 分支合并则无法删除

6. git branch -D a

   强制删除 a 分支 

7. git push origin master

   本地代码推送到远程 master 分支

8. git pull origin master 

   远程仓库 master 分支代码更新到本地

9. git remote -v

   查看当前仓库有哪些远程仓库

10. alias

11. git diff

12. checkout

    - 切换分支
    - 切换到某次 commit
    - 撤销功能：git checkout a.md

13. git stash 

    暂存，前提是代码没有进行 commit

14. git merge & git rebase