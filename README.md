# Hackintosh-deskmini-efi
Deskmini-efi for Hackintosh
> `Now available for 10.12.6、10.13.1`

# 1. 主机配置
* 华擎（ASRock）DeskMini110/COM
* I5 7500 3.4GHz
* HD630核显（CPU自带）
* ALC283声卡（主板自带）
* Intel I219V千兆网卡（主板自带）
* BCM94352Z（淘宝买的，当前使用）
* 8Gx2 2400 DDR4 金士顿笔记本内存
* 建兴（LITEON）睿速系列 T10 240G

# 2. BIOS设置
* Vt-d 关闭
* IOAPIC 24-119 Entries 关闭
* USB XHCI Handoff 打开
* IO串口 关闭
* 安全启动模式 关闭

# 3. Clover信息
clover：r4318
## 正常功能：
* CPU 变频正常
* BCM94352Z 正常
* 声卡-AppleALC原生驱动
* USB正常

## 待解决：
* 双屏输出

# 更新记录
2017-12.04

1. 更新 clover
2. 更新 kext（lilu-1.2.1，以及相关 kext）
3. 升级到10.13.1

2017-11.28

1. 更新说明

2017-10.27

1. update for 10.12.6
2. 原生 cpu 支持