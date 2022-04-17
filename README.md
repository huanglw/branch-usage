# branch-usage
branch usage testing.

# 相关命令 
git branch [branch-name]
git checkout [branch-name]
git checkout -b [branch-name]
git branch -a // 查看所有分支

# 相关分支
---main
   |
   --- branch_a
   --- branch_b
   --- branch_c

# 分支合并主分支的变更
- 切换到分支，git checkout branch_a
- 执行merge操作，git merge main

# branch_a修改
