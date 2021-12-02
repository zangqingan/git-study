# 一、git-study版本管理工具概述
github是为开发者提供git仓库托管服务的一个网站：https://github.com/
pull request是指开发者在本地对源代码进行更改后，向 GitHub 中
托管的 Git 仓库请求合并的功能。开发者可以在 Pull Request 上通过评
论交流，例如“修正了 BUG，可以合并一下吗？”以及“我试着做了这
样一个新功能，可以合并一下吗？”等。通过这个功能，开发者可以轻
松更改源代码，并公开更改的细节，然后向仓库提交合并请求。
任务管理和 BUG 报告可以通过 Issue 进行交互。
Git 属于分散型(分布式)版本管理系统，是为版本管理而设计的软件。
所谓版本管理就是管理更新的历史记录。

## 1.1 版本管理工具分类
集中型----以subversion(svn)为代表，它是集中的将所有数据存放到服务器上，优点是便于管理，其缺点是开发者所处环境不能连接网络时无法下载最新的源代码，服务器宕机也可能造成数据丢失。
分散型----以git为代表，它是将仓库fork(分支，分叉)给每一个用户，它是将原仓库复制了一份给开发者。这样每一个人都是单独的一份

# 二、Git初始化
因为Git是分布式版本控制系统，所以，每个机器都必须自报家门：
设置用户名：$ git config --global user.name "Your Name"
设置用户Email地址：$ git config --global user.email "email@example.com"
设置提高命令可读性：$ git config --global  color.ui auto
接下来就是添加一个GitHub账号
Follow（关注）别人，所 Follow 的用户的活动就会显示在您的控制面板页面
中。您可以通过这种方法知道那个人在 GitHub 上都做了些什么
Watch ()
还没有添加至 Git 仓库文件，所以显示为 Untracked files。

我是在dev分支下添加的内容，不合并分支前主分支是没有的



