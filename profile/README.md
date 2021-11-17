## 👋Welcome to Yimai's Org

# _Homework of Git Basics_

_本次push来自ubuntu20.04版本下一位不愿透露姓名的的超级用户_

***

学员：颜怡麦 Yimai Yan

![照片不是本人](..\png\11.jpg)

**照片非本人**

***

兴趣爱好：科幻和制作meme

![科幻meme](..\png\12.jpg)

![meme](..\png\13.jpg)

***

**第一次作业总结**

_环境配置_

* windows10系统
* Ubuntu20.04和Ubuntu原始版本分别都存在用户组
* gitbash用户组是YiMai，Ubuntu20.04用户组是yanyimai
* 使用vscode和Typora辅助编辑

_学到的知识_

* gitbash使用方法

* git在ubuntu中的操作

* 常见git指令

  ```
  git init/git status/git log/git add/git commit -m""/git branch/git checkout -b/git checkout -D/git reset/git pull/git push
  ```

* linux访问Windows文件（到相应文件夹中shift+右键选择linux shell）

  ```
  访问linux文件夹
  yanyimai@hannah:~$ explorer.exe .
  访问windows中的e盘中的steam.exe文件
  yanyimai@hannah:~$ cd
  yanyimai@hannah:~$ cd /
  yanyimai@hannah:/$ cd mnt /
  -bash: cd: too many arguments
  yanyimai@hannah:/$ cd mnt/
  yanyimai@hannah:/mnt$ ls
  c  d  e
  yanyimai@hannah:/mnt$ cd e
  yanyimai@hannah:/mnt/e$ cd
  yanyimai@hannah:~$ cd /
  yanyimai@hannah:/$ cd mnt/
  yanyimai@hannah:/mnt$ cd d
  yanyimai@hannah:/mnt/d$ ls
  '$RECYCLE.BIN'       LenovoSoftstore  'Program Files'        'System Volume Information'   jdk      steam
   DumpStack.log.tmp   MinGW            'Program Files (x86)'   WebStorm                     jdk17
   JetBrains           Nodejs            SteamLibrary           WindowsApps                  matlab
  yanyimai@hannah:/mnt/d$ find. | steam.exe
  
  Command 'find.' not found, did you mean:
  
    command 'findg' from deb ncl-ncarg (6.6.2-1build4)
    command 'find' from deb findutils (4.7.0-1ubuntu1)
    command 'findv' from deb polylib-utils (5.22.5-4+dfsg)
  
  Try: sudo apt install <deb name>
  
  steam.exe: command not found
  yanyimai@hannah:/mnt/d$ find . | steam.exe
  find: ‘./$RECYCLE.BIN/S-1-5-18’: Permission denied
  find: ‘./$RECYCLE.BIN/S-1-5-21-1103935815-1389928621-3828061750-500’: Permission denied
  find: ‘./$RECYCLE.BIN/S-1-5-21-4122960806-610405267-2663008296-500’: Permission denied
  find: ‘./$RECYCLE.BIN/新建文件夹’: Permission denied
  steam.exe: command not found
  yanyimai@hannah:/mnt/d$ cd
  ```

  

* Windows访问Linux文件

_没解决的问题_

* gitbash里面的用户是Yimai@DESKTOP，ubuntu里面是yanyimai@DESKTOP，非常迷惑，不确定这样子会不会造成冲突

* 电脑自带Ubuntu里面装了conda，不知道会不会有影响

* git push报错，重新提交之后又没事了。

  ```
  $ git push https://github.com/yimaiyan/demo.git
  fatal: unable to access 'https://github.com/yimaiyan/demo.git/': OpenSSL SSL_read: Connection was reset, errno 10054
  ```



* 还没用IDEA操作git，都是在用vscode
