# DELL-optiplex-9020
电脑配置：

电脑型号            戴尔 OptiPlex 9020

  处理器              英特尔 第四代酷睿 i5-4570 @ 3.20GHz 四核
  
    主板                戴尔 03CPWF ( Lynx Point Q87 )
    
    主显卡              英特尔 HD Graphics 4600 ( 戴尔 )
      
    声卡                瑞昱 ALC280 @ 英特尔 Haswell  高保真音频
    
    网卡                英特尔 Ethernet Connection I217-LM / 戴尔
    
  无线网卡              奋威 
  
  需要确认的是处理器、显卡、声卡、网卡的配置
  
#安装步骤：
1、设置BIOS;

?Boot sequence -> UEFI

?Advanced Boot Options -> Uncheck Enable Legacy Option ROMs - (only if graphics are UEFI capable)

?Serial Port -> Disabled

?Sata Operation -> AHCI

?Integrated NIC -> Enabled

?Secure Boot -> Disabled

2、制作安装镜像

镜像制作：下载etcher，打开镜像，选择U盘，点击Flash即可etcher

安装镜像的制作到这里就完成了,下一步,我们需要将EFI复制进刚制作好的USB磁盘的EFI分区里

3、将EFI复制到USB安装盘的EFI分区下替换

4、电脑U盘启动并安装系统；

5、如声音不正常将注入改为21

6、愉快的玩耍吧！！
