# ACER_E5_572_opencore_efi

#### 介绍
宏基笔记本E5 572黑苹果 opencore 0.62引导efi

#### 硬件配置
CPU:intel i5 4210m
GPU：HD4600/GT940m 2G
ETH Card：rtl8168
WIFI/BLUETOOTH: AR9565
HD: 500G
MEMORY: 4G DDR3L 1600
DISPLAY: 15.6 inch FHD 1920x1080
AUDIO card:	Realtek ALC283
HD WEBCAM:N/A ?
cardreader:N/A ?


#### 使用说明

1.  opencore 引导在黑果小兵引导文件基础上修改正常引导10.15.6/10.15.7
2.  DSDT/SSDT 均已提取修改、补丁
3.  CPU变频正常、核显正常、网卡正常、WIFI蓝牙正常驱动（但是有冲突，同一时间只能工作一个）、触摸板驱动正常（多指手势无法工作）、液晶屏幕背光PNLF可以在设置面板中调节
4.  睡眠未调试、读卡器不工作、airdrop等都未调试



#### 致谢

1.  https://github.com/Hlynford/Acer-E5-572G-528R-Hackintosh
2.  https://oc.skk.moe/
3.  https://blog.xjn819.com/post/opencore-guide.html
4.  hhttps://github.com/peng8350/E5-572G-EFI
5.  https://github.com/xxiaocheng/acer-e5-572g-536w-EFI