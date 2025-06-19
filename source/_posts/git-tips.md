---
title: Git小技巧
tags: Tech
---
## Git配置Beyond Comapre

#### 1. 配置Beyond Comapre作为Diff工具：
``` cmd
  git config --global diff.tool bc
  git config --global difftool.prompt false
  git config --global difftool.bc.path "c:/Program Files/Beyond Compare 4/bcomp.exe"
```
运行`git difftool main...feat/xxx --dir-diff`, 自动弹出BeyondCompare比较差异。
![image](https://github.com/BD-Joy/Continuous-Learning/assets/7828364/5d0fa648-0a5b-4b73-9bf1-6d9edb4cdd5c)


#### 2. 配置Beyond Comapre作为Merge工具
``` cmd
  git config --global merge.tool bc
  git config --global difftool.prompt false
  git config --global mergetool.bc.path "c:/Program Files/Beyond Compare 4/bcomp.exe"
```

参考：
https://www.scootersoftware.com/kb/vcs#gitwindows
