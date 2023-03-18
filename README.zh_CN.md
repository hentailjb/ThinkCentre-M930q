## ThinkCentre-M930q 黑苹果 OpenCore EFI

![image](Screenshot/m930q.png)

### [English](https://github.com/hackintosh-efi/ThinkCentre-M930q)


### OpenCore

[OpenCore 0.9.0](https://github.com/acidanthera/OpenCorePkg)


### 机器配置

- 主板: Q470
- 处理器: Intel i3-10105
- 内存: 三星 32GB(2x16GB) DDR4 2666 Mhz
- 显卡: 英特尔® 超核芯显卡 630
- 声卡: Realtek ALC233
- 硬盘: 西数黑盘 SN750 512G
- 网卡: Intel Ethernet Connection I219-LM
- 无线: BCM94360CS2（白果拆机卡）


### BIOS设置

```
设备
  |-- 串行端口菜单
    |-- 串行端口1: 关闭
  |-- ATA设备菜单
    |-- 配置SATA为: ACHI
  |-- 显示菜单
    |-- 选择有效显示: IGD
    |-- 预指派内存大小: 64MB
    |-- 全部显示内存: 最大

高级菜单
  |-- CPU菜单
    |-- Intel(R) HT技术: 打开
    |-- 多核心处理功能: 打开
    |-- Intel(R) Virtualization技术: 打开
    |-- VT-d: 关闭

安全菜单
  |-- 安全启动
    |-- 安全启动: 关闭

启动菜单
  |-- 极速启动: 关闭
```


### 系统截图

![macOS Ventura](Screenshot/about.png)

![Info](Screenshot/info.png)

![Geekbench 5](Screenshot/geekbench5.png)


### 驱动

- [Lilu.kext 1.6.4](https://github.com/acidanthera/Lilu)
- [SMCProcessor.kext 1.3.1](https://github.com/acidanthera/VirtualSMC)
- [SMCSuperIO.kext 1.3.1](https://github.com/acidanthera/VirtualSMC)
- [VirtualSMC.kext 1.3.1](https://github.com/acidanthera/VirtualSMC)
- [WhateverGreen.kext 1.6.4](https://github.com/acidanthera/WhateverGreen)
- [AppleALC.kext 1.8.0](https://github.com/acidanthera/AppleALC)
- [IntelMausi.kext 1.0.7](https://github.com/acidanthera/IntelMausi)


### 工具

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) 即 `OCC`。
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) 三码生成工具。
- [MountEFI](https://github.com/corpnewt/MountEFI) EFI 分区挂载工具。
- [EFI Agent](https://github.com/headkaze/EFI-Agent) 更方便的EFI分区挂载工具。
- [gibMacOS](https://github.com/corpnewt/gibMacOS) macOS 官方镜像下载工具。
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist 编辑器。
