# xray_launcher
## xray 启动器（linux/kali 用）

### 环境
- `python3`
- `xray_linux_amd64`

### 使用说明
- 将 xray linux 版主程序 `xray_linux_amd64` 放到和脚本相同
- 给 `xray-launcher` 执行权限
- 命令行运行 `./xray-launcher` 加上 xray 参数使用

```bash
┌──(kali㉿kali)-[~/xray_launcher]
└─$ ./xray-launcher -h

            launch xray before time.

Tue Feb  8 10:00:00 PM PST 2022

____  ___.________.    ____.   _____.___.
\   \/  /\_   __   \  /  _  \  \__  |   |
 \     /  |    _  _/ /  /_\  \  /   |   |
 /     \  |    |   \/    |    \ \____   |
\___/\  \ |____|   /\____|_   / / _____/
      \_/       \_/        \_/  \/

Version: 1.8.4/a47961e0/COMMUNITY-ADVANCED
...
```

### 主要功能：
- 从特定时间启动 xray

### 顺带可以
- 在 20220208 （xray-license.lic 过期前）启动 xray, 实现破解 xray

> 代码参考 [https://mp.weixin.qq.com/s/KfPIPHSjK815G_IXKtcImQ](https://mp.weixin.qq.com/s/KfPIPHSjK815G_IXKtcImQ)