#### keil的软件包安装（pack install）

##### 	2.5种形式：

​		1.直接使用Pack Installer。

​		2.在[Arm Keil | CMSIS Packs](https://www.keil.arm.com/packs/)下载软件包，然后在Pack Installer中导入。

​		2.5：

​		在[Arm Keil | CMSIS Packs](https://www.keil.arm.com/packs/)或其他方式下载软件包后，将软件包的.pack后缀改为.zip后缀后解压。

​		打开Keil安装路径，所在目录keil5-ARM-packs-keil，在此文件夹下新建名为"XXXX_DFP"的文件夹(名称为你要添加的芯片包的名称，如"Keil.STM32F2xx_DFP.2.9.0.pack"就填中间那段"STM32F2xx_DFP"，如下图
![在这里插入图片描述](../../../prosws source/Typora/imgs/dc3fec3aa988af213b46f3a5d5474b54.png)

​		进入文件夹，并新建名为芯片包版本号的文件夹，并把解压出来的所有文件全部复制到该文件夹里，如下图
![在这里插入图片描述](../../../prosws source/Typora/imgs/9e0e07f15992901975737666e54dd71d.png)



参考文献：[Keil安装芯片PCAK包失败/软件卡死/无法解压的问题_keil pack包安装错误-CSDN博客](https://blog.csdn.net/xingqingly/article/details/135880629)

