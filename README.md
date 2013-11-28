###################################项目简介################################
简致阅读，是一个专注于阅读的平台，为零散时光的精致阅读体验而生，我们不做长篇连
载，不做收费和广告，我们也不创作文章，我们只做精致短文的搬运者，当你沉溺在都市
的喧嚣里无法自拔，当你想回归那宁静质朴的文字世界，却被一张张花哨的网页，纷飞的
广告，边栏扰乱了注意力的时候，请来简致阅读坐坐吧。

简致阅读的文章来源于互联网，是用一种半自动的方式搜集的，之后会经过再提取，再排
版，存储在我们的数据库中。之所以选择半自动的方式正是我们的设计理念，在最大程度
的保证文章质量的基础上再去考虑运行成本。


###################################项目组成################################
整个项目包括服务端，网页网站，客户端三大部分，其中服务端建立于GAE的基础上，是
整个项目的基础，所有的采集，提取，排版工作均运行于服务端；我们为项目建立了一个
网站（http://www.jianzhiyuedu.com），在上面除了提供阅读功能外，还有项目的相关
信息，作者联系方式，客户端下载链接，以及最新的项目动态；客户端即PC客户端和移动
客户端（目前支持WP8，Android，IOS），提供了不同于网页端（我们有手机版网页）的
拓展功能，包括离线缓存，文章下载等，更加易用。


###################################仓库详情################################
本仓库并不是整个项目的基地，只包含了服务端的部分核心代码（采集 提取），并不含有
GAE相关的部分，如果你对GAE的相关部分感兴趣，请访问网站获取相关信息；客户端的全
部源码（除WP8平台）都可以在该仓库中找到。
下面列出目录结构与对应内容：（origin）
1.	server/ 	------------------	服务端
2.	client/ 	------------------	PC客户端
3.	android/	------------------	Android客户端
4.	ios/    	------------------	IOS客户端	


###################################作者信息################################
我是oOXuOo，简致阅读的发起者之一，也是Android，IOS客户端的作者，同时负责服务器
后端的文章采集和文章源的控制。喜欢开源技术，喜欢精美文章，如果你对该项目感兴趣，
请电邮我：2297880491@qq.com ; olmpichero@163.com
此外，如果你对GAE与服务器搭建，或者网页网站感兴趣，可以再www.jianzhiyuedu.com
上找到其他作者的联系方式。


###################################开源公告################################
整个项目（指该仓库中的全部，其他部分正在协商中）将采用GPL的协议授权。GPL授权的
具体信息请仔细阅读 License 文件，再此不赘述。
整个项目中使用了大量的开源组件，现做出公告：
1. 整个服务端的全部代码由Python写成，构建并运行于GAE之上，感谢Python社区写出了
那么多好用的Python标准库；

2. PC客户端目前由Python写出主要原型，并且目前为命令行可用，后期将可能用PyQt实
现用户界面，而跨平台的打包工作初期用PyInstaller实现；

3. 移动端采用同一套编码，使用了QT项目的最新技术QtQuick和QML，十分感谢他们的创造
性工作，使我这样的C/C++程序员可以避开重新学习Java，ObjC的烦恼，开发出跨平台的移
动应用。














