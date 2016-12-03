# sublime-config

本仓库记录了我 **Sublime Text 3** 的个人配置，方便备份和还原Sublime。

关于Sublime的用法可参考我的博客：[Sublime Text 使用小结](http://tanchao90.com/2016/04/18/sublime/)

我的信息：
- OS：Windows 10
- Sublime Text：Build 3126


### 用法
进入到Sublime用户配置文件所在目录（Sublime Text 3\Packages\），然后执行下面的命令即可：

**方法1**：若目录下有对应的同名文件，`git pull origin master`会失败，需要先删除对应文件
```git
git init .
git remote add origin https://github.com/tanchao90/sublime-config
git pull origin master
```

**方法2**：会覆盖同名文件，所以**如有特殊配置，请提前备份**
```git
git init .
git remote add origin https://github.com/tanchao90/sublime-config
git remote update
git checkout -f master
```

clone 到本地之后，打开Sublime时Sublime会自动根据配置文件下载安装对应的插件，非常方便。

**注**：上述操作可能受限于网络，最好翻墙。

我的配置文件全路径是： `C:\Users\用户名\AppData\Roaming\Sublime Text 3\Packages\`

不知道配置目录的可按下面步骤找：

1. 点击 `Preferences/Browse Packages`；
2. 弹出的目录即是 `Sublime Text 3\Packages\` 目录；


### Reference
- [How to get Git to clone into current directory](http://stackoverflow.com/questions/9864728/how-to-get-git-to-clone-into-current-directory/33695754#33695754)
