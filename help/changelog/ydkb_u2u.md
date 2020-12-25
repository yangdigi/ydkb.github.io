# YDKB优联系列U2U固件更新记录
[+]新增 [-]删除 [^]升级 [#]修复 {}重要

受限存储空间，本固件不支持的功能有：电源、睡眠等按键，启动快捷方式功能，设置默认层，LEDMAP，左右Shift命令按键，内置宏等。

受限于优联本身，不支持任意6键无冲当然更不用提全键无冲了。

目前来说大部分YKDB支持的功能，此固件均已支持，我已经尽全力了。

##### 2020-03-19 (DK3J) 
  - {+} 极大地完善鼠标支持，现在插在U2U的接收器，再配对一个优联鼠标，使用体验完全可以接受了。注：鼠标只支持 移动和左右中前进后退五个按键，这五个按键支持重定义，连接到U2U接收器上的鼠标，不支持罗技的驱动功能。
  - [-] 去除了RGB指示灯的改装（基本没人用），而且需要去除来节约空间给鼠标功能。
  - {+} 因为此固件已经添加鼠标功能，所以不在键盘列表里再单独列出YD40w_v1，同时YD40w_v1的用户需要重新设置一次按键。
  - {+} 添加SEND KEYMAP的功能，具体使用说明见__[[edit-keymap:load-keymap|读取按键]]__
  - {+} 添加LT(S)功能，具体区别见__[[en:edit-keymap:layer-tap-key|Layer Tap Key]]__
  - {^} 左Ctrl+Reset跳转到刷机模式，同时支持使用Arduino Bootloader和DFU Bootloader的设备。