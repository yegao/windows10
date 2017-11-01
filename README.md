ctrl+space被输入法占用,导致某些IDE改快捷键无法使用
----
win+R 调出运行窗口
输入“regedit”,调出注册表
修改HKEY_CURRENT_USER\control panel\Input Method\HotKey中的key modifiers和virtualkey的第一个字节为00
同样的路径设置和HKEY_USERS的两个字节
重启系统