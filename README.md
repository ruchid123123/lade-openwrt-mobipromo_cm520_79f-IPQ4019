# lade-openwrt-mobipromo_cm520_79f-IPQ4019

## 一、目的：

> 提高上网速度

## 二、方法：

> 使用lade最新源码编译星际宝盒的固件，只安装ssr和mosdns两个插件。

### 1.vmware16下载连接

> https://download3.vmware.com/software/wkst/file/VMware-workstation-full-16.0.0-16894299.exe

### 2.vm16激活码

> ZF3R0-FHED2-M80TY-8QYGC-NPKYF

### 3.ubuntu20.4ltsc下载链接

> https://releases.ubuntu.com/focal/ubuntu-20.04.6-desktop-amd64.iso

### 4.lade代码源码

> https://github.com/coolsnowwolf/lede

### 5.实际方案

* 由于虚拟机无法运行，最终实际上使用的是在实体机上安装mint linux系统进行编译。
* ***还可以使用github的在线编译，但此功能不熟悉还不如不用***
* 2024年1月3日编译失败，使用的恩山论坛已有的编译好的固件，使用的是passwall
* x86的可以使用这个连接：https://openwrt.mpdn.fun:8443/?dir=lede

## 三、结果

* 使用速度有提升

## 四、结论：

* 精简插件数量有助于加速软路由上网速度
