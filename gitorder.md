### gitorder
- git init //在当前文件夹下初始化git创建本地git仓库
- git status //查看当前仓库状态，会显示当前添加的文件和修改的内容
- git add <filename> //将当前文件添加到暂存区  . 代表所有文件
- git rm --cached <file> //使用该命令可以将add添加到暂存区的修移除
- git commit //将当前暂存区的修改提交
- git config --[where] user.name "" //添加姓名  -- system --global --local
- git config --[where] user.email "" //添加email 
- git config --[where] --unset user.name //删除配置

git文件状态
![文件状态图](./img/pic1.png)

### linux 命令
- cd [path]
- mkdir [packagename]  //创建文件夹
- touch [filename]  //创建文件
- cat [filename]  //查看文件内容
- vim [filename]  //编辑文件

###其他
git 提交的id 是一个摘要值 实际上是
设置username 和user.email 有三个地方
1. /etc/gitdonfig(几乎不会使用)所有用户的信息都会用到这个 git config --system
2.  ~/.gitconfig (很常用) 用户主目录之下的配置文件 git config --global 
3. 针对于特定项目的 .git/config 文件中  git config --local
