![Xray](https://github.com/mingxiaoyu/lede-ssr-plus/workflows/Xray/badge.svg)

![SSRP](https://github.com/mingxiaoyu/lede-ssr-plus/workflows/SSRP/badge.svg)

中文：通过openwrt-sdk-armvirt-64的SDK编译IPK，我个人用于Phicomm N1.理论上所有arm64的openwrt都可以使用
# 如何安装ipk

1. 命令行

使用Winscp将ipk上载到openwrt，然后通过ssh连接到openwrt：

```console
  opkg install [文件夹路径]/IPk名
```
2. Openwrt UI

菜单: 文件传输 - > 选择文件 - >  上传 - > 安装

![FileTransfer](https://github.com/mingxiaoyu/lede-ssr-plus/blob/main/imgs/opkg_install.PNG?raw=true)

English Version: Ipk is compiled by openwrt-sdk-armvirt-64 SDK, which I personally use for phicmn1. Theoretically, all openwrt of arm64 can be used

# How to install the ipk

1. Command

Use Winscp to upload ipk to your openwrt, and then connect to openwrt via ssh:
```console
  opkg install [file's path ]/ipk's name
```
2. Openwrt UI

Menu: Filetransfer - > Select the file - >  Upload - > Install

![FileTransfer](https://github.com/mingxiaoyu/lede-ssr-plus/blob/main/imgs/opkg_install.PNG?raw=true)
