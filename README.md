# asus_v5000j_clover_efi

华硕VivoBook S15 V5000JP笔记本黑苹果引导文件，版本 V5000J，CPU：i5 1035G1，硬盘：Intel pcie ssd 512GB

# 安装的注意

1，bios里只需要修改硬盘模式为AHCI，不能使用Intel RST；

2，如果用移动硬盘当刻录安装盘，必须用transmac，速度很快哟。

3，安装的时候用这里的CLOVER里的config.plist和kext/ 覆盖替换进刻录安装盘的对应位置

4，然后从clover启动安装。opencore没试过。

# 目前已驱动了项目：

显卡 ☑️

亮度调节 ☑️（须手工调节）

声卡 ☑️

网卡 ☑️（非完美）

蓝牙 ☑️

电池管理 ☑️

触摸板 🈲️ （还没搞定）

自带摄像头 🈲️ （还没搞定）

# 进入MAC后的注意

1，wifi需要先安装新版本的heliport，然后重启就可以选择wifi了。懂linux命令的，可以直接去/EFI/CLOVER/kext/Other/itlwm.kext/Content/里，修改Info.plist里的ssid和password字段。写死了热点名称。

2，如果没有声音，需要去设置的声音里，修改输出为speaker即可。装好黑苹果的默认输出好像不是speaker。

3，蓝牙连接蓝牙鼠标好像不能用。但是连接蓝牙音箱、耳机都正常，开机还能保持，非常棒。

4，如果需要装xcode，xcode需要35GB的空白空间，所以建议给黑苹果的分区要大于80GB，且进入黑苹果后能联网了先装xcode，再装其他软件。

5，鼠标必须用USB接口的鼠标。触摸板还没解决啊！！


# 好玩的应用
1，lol可以玩，只有美服，延迟感人

2，wow的新世界和怀旧服都能玩，效果非常赞

3，如果遇到死机，鼠标不能动，强制关机后重启2次就活蹦乱跳了。


