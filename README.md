# xujc-RouterAutoConnect
厦门大学嘉庚学院宿舍校园网自动连接脚本

把xujc-RouterAutoConnect放入/etc/init.d

把.sh文件放入/usr/lib/xujc-RouterAutoConnect

使用ssh在openWRT路由器的的Shell环境变量中设置写入自己的学号（userId）、密码（password）和指定运营商代码（见下表）

|运营商代码|运营商名|
|-|-|
|campus| 校园网|
|telecom| 中国电信|
|mobile|中国移动|
|unicom|中国联通|

```shell
/etc/init.d/xujc-RouterAutoConnect start
```
脚本会自动检测在线状态并重连
你也可以手动运行代码

