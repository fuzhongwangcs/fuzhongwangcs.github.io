---
layout: post
title: Python环境的搭建（windows环境）
excerpt_separator:  <!--more-->

categories:
  - Python
tags:
  - Python
  - readability
  - standard
---


------

### **1、首先访问[http://www.python.org/download/][1]去下载最新的python版本。**
　　到这里大家会遇到一个问题，该学习Python2还是Python3版本呢？  

　　Python3一定是未来的趋势，可是它不支持向下兼容，也就是用python2.7版本编写的代码，没法在python3中直接运行，而在python2.7中却可以应用一些python3的语法。当然，Python3有它的好处，它的源码默认就是UTF-8编码，这样就不需要现将中文转换编码了，可以直接使用和输出中文。在Python2中使用的print输出语句，在3版本中变成了一个叫做print()的函数，例如输出print“helloiplaypython”，现在变成了print(“iplaypython”)。现在很多Python书籍中都在使用Python2版本做为教程示例，尤其是现在大多数第三方库都没有完全移植到python3版本，如果直接选择学习Python3版本，将面临非常大的难题，很多python模块没办法正常使用，一些WEB框架，如果Web.py、Django等，对python3支持的都不算好，或者根本没有正式的支持。建议初学者先学习Python2版本，之后依照个人情况，再选择是否学习3版本的Python语法。  

　　　　　![][2]
### **2、安装下载包，一路next。**
### **3、测试python安装是否成功，cmd打开命令行输入 python 命令，如下图即成功了**
　　　　　　![][3]
### **4、Hello World！ 按照很多资料上写的，输入 print 'Hello World!'**
  　　　　　　![][4]
### **5、经过以上测试，python环境算是装好了，但是怎么开发呢，难道用这种命令行？**
　　有很多IDE可以应用，对于个人而言，IDE的话推荐PyCharm，编辑器的话推荐VS Code。  

　　PyCharm安装教程：  

　　①、到[PyCharm官网][5]下载PyCharm安装包。
　　　　　　　　![][6]
　　②、选择Windows系统的专业版下载。
　　　　　　　　![][7]
　　③、双击安装包进行安装。
　　④、安装完成，勾选立即运行PyCharm。
　　　　　　　　![][8]
　　⑤、选择是否导入开发环境配置文件，我们选择不导入。
　　　　　　　　![][9]
　　⑥、选择输激活服务器激活软件。激活服务器地址:http://idea.imsxm.com/  

　　初期工作就是这样了。

  [1]: http://www.python.org/download/
  [2]: https://thumbnail0.baidupcs.com/thumbnail/f0fa471c10bbb26652764406f5020400?fid=1550860239-250528-784725689504947&time=1515744000&rt=sh&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-NWuUKLzZgYsGZ%2bLbees/DtQ6mfo=&expires=8h&chkv=0&chkbd=0&chkpc=&dp-logid=271286973956028332&dp-callid=0&size=c710_u400&quality=100&vuk=-&ft=video
  [3]: https://thumbnail0.baidupcs.com/thumbnail/7f7b2e4c8d798770f19b3197d5a1e342?fid=1550860239-250528-557166975384135&time=1515744000&rt=sh&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-n7y6mWeprGjKhcAxLlhfkqLETKw=&expires=8h&chkv=0&chkbd=0&chkpc=&dp-logid=271401991114918668&dp-callid=0&size=c710_u400&quality=100&vuk=-&ft=video
  [4]: https://thumbnail0.baidupcs.com/thumbnail/c36041271acf59d42d17cd11ac50710b?fid=1550860239-250528-85097964656274&time=1515744000&rt=sh&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-bQ1b9ygsaisOyiJ46NV4L/J6I%2b8=&expires=8h&chkv=0&chkbd=0&chkpc=&dp-logid=271440227049616435&dp-callid=0&size=c710_u400&quality=100&vuk=-&ft=video
  [5]: https://www.jetbrains.com/pycharm/
  [6]: https://thumbnail0.baidupcs.com/thumbnail/defd94ca02bfb94e50edcc6ec2a4def3?fid=1550860239-250528-466218469166190&time=1515762000&rt=sh&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-G1yZPARtU8SzfX/yMiMKJjOYEZw=&expires=8h&chkv=0&chkbd=0&chkpc=&dp-logid=276190889043403585&dp-callid=0&size=c710_u400&quality=100&vuk=-&ft=video
  [7]: https://thumbnail0.baidupcs.com/thumbnail/ee1ce78fae88a379c180b866da932c28?fid=1550860239-250528-334793423984628&time=1515762000&rt=sh&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-Fjf4WM8kkgUpXZjbKyuX4J63OBk=&expires=8h&chkv=0&chkbd=0&chkpc=&dp-logid=276204977511078130&dp-callid=0&size=c710_u400&quality=100&vuk=-&ft=video
  [8]:https://thumbnail0.baidupcs.com/thumbnail/1cbde3de5eb4d3f2b0056b46f6339506?fid=1550860239-250528-343372964619771&time=1515765600&rt=sh&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-cr7ZhMRKzvqrzvtIQ12UpUcSODE%3D&expires=8h&chkv=0&chkbd=0&chkpc=&dp-logid=276388999999317472&dp-callid=0&size=c710_u400&quality=100&vuk=-&ft=video
  [9]:https://thumbnail0.baidupcs.com/thumbnail/f11c14a01b7e4fcefc70645e88351ffc?fid=1550860239-250528-506717621386713&time=1515765600&rt=sh&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-E54rDTCEBOw9pi4BCd1%2FbJoEPs0%3D&expires=8h&chkv=0&chkbd=0&chkpc=&dp-logid=276425859353730501&dp-callid=0&size=c710_u400&quality=100&vuk=-&ft=video