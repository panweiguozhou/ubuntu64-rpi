# RaspberryPi3-ubuntu-16.04-aarch64          [English](https://github.com/chainsx/ubuntu64-rpi/blob/ubuntu-16.04-arm64/README-EN.md)
### [64位centos戳这里](https://github.com/chainsx/centos64-rpi)
# 经测试，性能最高提高60倍!!!

****************

## 前言：
#### ubuntu官方居然不给RaspberrPi3出官方镜像（官方推荐的镜像是Electron752移植的。。。。），太不厚道了。（但据说是因为16.04何rpi3发布时间隔的太近了）

## 声明：
* 本系统由我（chainsx）自行构建的根目录以及boot。
* 如需定制版以及商业用途，请**务必**与本人联系。
* 可以转载，推广甚至修改本系统，但**必须注明出处**。
* 你可以基于本系统打造更加完善的系统，但**必须注明出处**。
#### …………

## 一些拓展功能（没必要的话就别开启）：

* 因为是64位系统，所以你可以开启32位支持,[开启方法](https://github.com/chainsx/ubuntu64-rpi/blob/ubuntu-16.04.3-arm64/Documentation/32-bit-support.md)

* 为不同的架构指定不同的源，[点此查看](https://github.com/chainsx/ubuntu64-rpi/blob/ubuntu-16.04.3-arm64/Documentation/multi-arch.md)

* 添加树莓派官方软件源镜像安装树莓派官方提供的特有的软件包，[添加方法](https://github.com/chainsx/ubuntu64-rpi/blob/ubuntu-16.04.3-arm64/Documentation/multi-arch.md)

* 添加swap分区，[添加方法](https://github.com/chainsx/ubuntu64-rpi/blob/ubuntu-16.04.3-arm64/Documentation/multi-arch.md)

## 关于:

* 本系统是直接基于ubuntu-Base-16.04-arm64构建的根目录， **非移植版** ，所以稳定性有提升，但是整个系统不够完善。
* 现在的开机时间不到10秒，超过了官方raspbian lite,吊打同类的pi64(国外人士移植的debian arm64)。
* 本系统由以下组成
#### **firmware** ：由树莓派基金会官方提供的linux-rpi-4.11.y编译的aarch64内核
#### **rootfs** ：ubuntu-Base-arm64(根目录构建)
* `apt`的源默认为清华软件源
* 默认用户：`ubuntu`      密码：`ubuntu`
* 支持wifi，配置方法[在这里](https://github.com/chainsx/ubuntu64-rpi/blob/ubuntu-16.04.3-arm64/Documentation/wifi-config.md)。
* 如果你需要安装桌面的话，[看这里](https://github.com/chainsx/ubuntu64-rpi/blob/ubuntu-16.04.3-arm64/Documentation/install-desktop.md)
* 默认开启ssh，不想要的自己去关。
* 默认为命令行，想要图形界面的自己装
* 第一次开机时不会拓展rootfs分区，意思是**需要你自己拓展**，用fdisk或gparted来拓展吧。
* 关于ext4的扩容方法，在[这里](https://github.com/chainsx/ubuntu64-rpi/blob/ubuntu-17.04-arm64/Documentation/expand-file-system.md)。


|  联系方式   |           |
|-----------|------------|
|QQ|1396219808(CX_rootfs)|
|E-mail|chainsx@outlook.com i@chainsx.cn|

**********************

## 下载地址：

### 腾讯云(tencent cloud)
##### （如遇公网流量达到上限而不可下载时请使用百度网盘）
##### 注意：公网流量有限，请不要使用例如迅雷，快车，电驴，ADM，aria2等下载工具下载，请使用浏览器内建下载/wget等非分块下载的工具下载，感谢你的支持。
### 发现有人恶意下载耗费大量公网流量，现暂时关闭腾讯云下载方式。

|文件系统 | 普通下载 |cdn下载 |
|-----|------|---------|
|使用EXT4文件系统|  |  |

### 百度网盘(Baidu Netdisk)

| 版本 | 下载链接 |
|--------|--------|
| stable(稳定版) | [链接](https://pan.baidu.com/s/1snt6ByX) |

# 欢迎加入树莓派64位系统交流群，QQ群号码：697381661
