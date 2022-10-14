#3 Linux / WSL
呜呜呜纯小白在翻墙翻了一天之后终于在9.7号的晚上成功安装好了github,vscode,markdown,虚拟机Linux Ubuntu了！太不容易了（掩面哭泣:sob::sob:）

####一、安装虚拟机且在虚拟机中安装配置 Ubuntu

在clash官网买好稳定的vpn之后（并且知道到底什么是翻墙。。。~~好孩子从不翻墙:doge:(手动狗头)~~），安装完vscode和github，对查找资料以及执行操作电脑稍微熟悉之后，虚拟机的安装稍微顺利了那么一丢丢（然而还是有些意外hhh...）

#####安装前看教程上说安装Linux系统会把其所在的磁盘格式化，吓得我赶紧又取消安装，因为。。。我发现我这台新win11电脑上没有此电脑!甚至只有一个C盘（之前我真心没见过这个问题呜呜呜:cry:），然后一一在网上找办法解决。

*分了两个盘：*
![分了两个新磁盘出来](https://s3.bmp.ovh/imgs/2022/09/11/02819524076fbb9d.png)

*然后开始按照教程把虚拟机文件放在了G盘，开始安装虚拟机：*
![根据网上教程安装虚拟机](https://s3.bmp.ovh/imgs/2022/09/11/f2ccfab91ff18e1f.png "根据网上教程安装虚拟机")
*安装Ubuntu Desktop*
![安装Ubuntu Desktop](https://s3.bmp.ovh/imgs/2022/09/11/886dd19b52022ec3.png "安装Ubuntu Desktop")
**安装好啦**
![](https://s3.bmp.ovh/imgs/2022/09/11/a03cdfa4f50b487d.png)
![](https://s3.bmp.ovh/imgs/2022/09/11/bfca691ce649d7c1.png)
**看到成功的那一刻真的成就感满满:grinning::smile:撒花撒花！！（~~虽然但是我发现好像跟磁盘没什么关系。。。~~）**

####二、通过 VScode 的 Remote 插件连接至你的虚拟机 / WSL2
*寻找教程：*
![](https://s3.bmp.ovh/imgs/2022/09/11/8cc46b85faf71113.png)
![](https://s3.bmp.ovh/imgs/2022/09/11/8cecfa11e67b1833.png)
发现需要现在Ubuntu上先打开SSN连接，且需要输入命令得到ip地址，再将IP输入vscode的remote插件中。

*找Ip地址：*
![找ip地址](https://s3.bmp.ovh/imgs/2022/09/11/403e7e70f3ab77aa.png)
*在虚拟机中打开SSH连接*
![](https://s3.bmp.ovh/imgs/2022/09/11/a5b562deff3d3b3b.png)
**SSH连接完毕**
![](https://s3.bmp.ovh/imgs/2022/09/11/88ef97f8df4a8349.png)
*到这儿长吁一口气，呼————*以后应该会知道它们的方便之处了吧！

####三、开发出简易的 Shell 小程序
参考：百度，b站黑马程序员

*先在虚拟机上安装vim*
![vim](https://s3.bmp.ovh/imgs/2022/09/12/dd5ac95a7a3a1bc5.png)
*创建shell程序："hello.sh"*
![shell](https://s3.bmp.ovh/imgs/2022/09/12/794b2b78c77727ab.png)
*使其有效后运行成功！！*
![hello](https://s3.bmp.ovh/imgs/2022/09/12/1fc899ebf1052af7.png)
接下来，在网上学习了下shell语言，还做了两页笔记呢（小骄傲）
在实践过程中，经过了多次报错，屡战屡败，屡战屡败（小白的摸爬滚打:heart_broken:）最终决定做一个简单的计算器！（总比hello难吧哈哈哈哈）

**进阶：做一个简单的计算器**
最大的感受就是：shell的里的空格坑的我好惨呐啊啊啊啊（bushi）
![calculator](https://s3.bmp.ovh/imgs/2022/09/12/ce49941196dbba2e.png)
最后运行成功啦！
![](https://s3.bmp.ovh/imgs/2022/09/12/7b02f8c59ec00188.png)

接下来几天我打算好好看一下黑马程序员的讲解再进一步实践，还是好多东西一知半解的，加油:fighting:！！
