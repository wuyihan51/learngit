Git is a version control system.
Git is free software.

git add .
git commit -m "meg"

git status
if modified, check: git diff

git log: watch the history change
git reset --hard commit_id
git reflog: seek the history command and back to future


工作区 git checkout -- file
暂存区分两步，第一步用命令git reset HEAD <file>，就回到了场景1，第二步按场景1操作
版本库 参考版本回退一节 git reset --hard commit_id