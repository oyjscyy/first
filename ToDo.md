1. markdown 就是一个非常好用的文本编辑器，并且很多README的格式就是markdown (.md)，有啥特色请知乎或者百度

2. 了解github， git， ssh

   - github和git的区别是啥
   - git 是什么，本地/云端。。。
   - ssh又是啥 
   - 什么是公钥（public key）和私钥？和ssh命令的关系（提示：命令ssh-keygen）？为什么要用到（如git clone）
   - git基本命令（clone, init, add, commit, push, fetch, checkout, branch) 

3. 创建project（本地ubuntu）

   - 创建项目文件夹（mkdir)（注：可进入/mnt/d（windows d盘）或/mnt/c，相当于用linux操作windows文件夹）
   - 进入文件夹（cd）
   - git 初始化（git init）
   - 将oycpp.md放入其中（mv或者拖动）
   - 查看git状态（git status），看到该文件unstaged
   - stage该文件（git add）
   - commit（git commit）并且进入vim编辑器写上传信息（按 **i** 进入insert模式开始编辑）“Initial commit" （写完**esc**，输入**":wq"** 退出。
   - （你可以顺便去了解一下vim是个什么样的东西）
   - 定期查看git状态（git status）

4. github创建一个repo

   - 设为私密，邀请我
   - 本地add此远程repo，命名为origin：git remote add origin git@.......
   - 本地push到origin指向的repo：git push -u origin --all
   - 在github上可以看到两条分支（branch），默认是main，另一条是本地的master，master中应包含.md文件

5. 项目准备

   - 大概了解命令行游戏风格，https://itsfoss.com/best-command-line-games-linux/ 参考Backgammon和2048

     （大概就是没有鼠标，键盘输入，程序给输出，同时尽量避免用户输入错误直接程序崩溃）

   - 大概规划（纸牌）游戏？（也可以不是纸牌

   - 写个md文件描述一下...?

6. 