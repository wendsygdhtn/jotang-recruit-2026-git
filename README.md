# |🍬🍬|-recruit-2026-git
111  
222  
333  

 
 











学习过程及笔记
0.我用steam++ 加速了Github
 
1.编辑readme.md时不能直接打回车换行，要打两个空格再回车或直接加空行来实现换行。

2.我下载并配置了Git最新版

3.我将之前储存我代码的一个文件夹转变为Git仓库，新建了txt文件，然后使用add，commit，log命令将其加入版本库并查看记录。

4.尝试了版本回退和返回

笔记

commit message:提交时的注释

指令  
1.仓库建立：在某文件夹中右键open git bush here,在命令行输入git init建立  

2.加入版本库：git add（+ 文件名） 接git commit-m""（暂存和提交）（文件修改后可再次提交新版本）  

3.查看仓库状态：git status  
其中文件的三个状态：  
红色：未被git跟踪的文件  
绿色：被add到暂存区的文件，但未提交  
消失：已存入历史库，status中将不再显示  

4.查看历史提交记录：git log，（加 --pretty=oneline可获得简省的记录）  

5.查看被修改的对象：git diff（不包括Git还未跟踪的对象）

修改提交后，用git diff HEAD -- xxxxx.txt命令可以查看工作区和版本库里面最新版本的区别

6.版本回退：git reset --hard HEAD~n（回退数）/HEAD(^^………^)(n个^)

返回新版本/回退至前版本：git reset --hard xxxxx(版本号前几位，可通过git log或git reflog查询）

7.撤销修改：git checkout -- readme.txt使文件回退回上次add或commit时的样子









