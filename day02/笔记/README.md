# 笔记

## Linux命令使用技巧

```
命令 -h
命令 --help
```

## git remote

fgit remote 是用来对远程仓库别名的配置

```
git remote add origin https://github.com/wzy782762257/H5NodeJs.git
```

- add 添加别名
- origin 别名(小名)
- url 远程仓库的地址

这里用来查看本地仓库的[别名配置]

```
git remote -v
```



## git push

push 推 推送 git push 将本体仓库的某个[分支]推送到远程仓库

```
git push -u URL/别名 分支名称
```

- -u设置本地分支与远程仓库分支的 [关联]



# 浏览器新窗口打开网页的小技巧

### Ctrl + 鼠标点击



# 分支不同名的情况(了解)

- git push origin dev:master



# 原则

### 不要在主分支上直接提交代码



# 免密提交

1.在git bash中运行ssh-keygen

2.生成两个文件 id_rsa 私钥 id_rsapub 公钥

3.将id_rsapub 文件的内容,复制-> 配置到gitee 上->gitee右上角头像->设置->ssh公钥->设置标题和公钥

4.使用仓库URL的时候选择 git@gitee.com 的形式