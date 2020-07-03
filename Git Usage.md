# Git Usage:

[TOC]

#### `CD`进入本地目录：

> // cd 文件路径
>
> PS C:\Users\Administrator> cd C:\Users\Administrator\Desktop\git-test

使用`git clone url`克隆仓库到本地

> // `git clone + url`
>
> PS C:\Users\Administrator\Desktop\git-test> git clone https://github.com/ouywy/git-test.git

#### `git status `查看工作区文件的状态

> `git status` 可以查看工作区文件的状态



#### `git add` 添加代码到暂缓区

> `git add` 把工作区中的代码添加到暂缓区
>
> > `git add .` 添加全部文件，也可以指定文件名(文件名加后缀)如：
> >
> > PS C:\Users\Administrator\Desktop\git-test\git-test> `git add test.py.txt`



#### `git commit -m "提交描述"` 提交分支

> git commit -m "commit test"



#### `git push` 上传代码到远程仓库

> `git push` 需要验证身份



#### `git pull` 拉取远程仓库的某个分支的更新，再与本地的指定的分支合并

> 基本用法：
>
> `git pull <远程仓库名> <远程分支名>:<本地分支名>` 如：
>
> git pull origin master:brantest
>
> 将远程主机origin的master分支拉取过来，与本地的brantest分支合并





在本地代码仓库中有以下概念：

- `.git`是代码仓库：
  - 暂缓区
  - 分支：默认`master`

- `.git`之外是工作区

#### git 图解：

<img src="E:\笔记\img\git-usage.png" alt="git 原理" style="zoom:110%;" />