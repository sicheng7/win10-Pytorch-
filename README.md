# Win10 环境下Pytorch安装
## 1、 打开anaconda prompt
## 2、新建一个虚拟环境 执行命令
- conda create --name pytorch1_7 python=3.6 
其中，python1_7是自定义安装名称
## 3、激活环境
- conda activate pytorch1_7
## 4、查看已安装的cuda版本号
控制面板->小图标->NVIDIA 控制面板-> 帮助-> 系统信息-> 组件
![image](https://user-images.githubusercontent.com/44308340/134904591-661b8594-e250-486c-a16d-34d3b449285e.png)
## 5、打开pytorch官网，进入下载安装页面 https://pytorch.org/get-started/locally/
选择相应的版本号
![image](https://user-images.githubusercontent.com/44308340/134905246-a178c886-40b5-41e7-93f5-acf7cb717187.png)

执行相应命令，即可完成安装 
注：此安装过程会出现有些包安装失败的情况，可通过多次执行该命令，重新安装缺失的包。
