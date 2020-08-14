# 小仓唯bot 一键安装脚本

小仓唯bot是基于 hoshino 与 yobot 的一个综合性公主连结机器人，功能繁多，操作简单，安装便捷，并且集成了很多当前流行的 bot 插件。

功能表：https://xcw.pcrbotlink.top/help.html

## 安装步骤

### Windows

**仅限 Windows 8 64位 或 Winodws 2012 R2 64位 以上系统运行**

**推荐在干净的，之前没有装过类似的bot的环境中运行(若有多个Python版本，请先全部卸掉)**

在合适的位置(**路径不要有中文**)打开 `powershell` 中执行：

```powershell
Invoke-WebRequest http://ftp.pcrbotlink.top/install.ps1 -OutFile .\install.ps1 ; powershell -File install.ps1
```

**注：提示"无法加载文件 ./install.ps1，因为在此系统中禁止执行脚本。有关详细信息，请参阅 "get-help about_signing"。"？
      解决方法：管理员运行powershell，执行"set-ExecutionPolicy RemoteSigned"，选择"[Y] 是(Y)"。**

### Linux

**目前暂时没有小仓唯的Docker镜像，可以先使用@LQBing的原版yobot+Hoshino镜像：
https://github.com/LQBing/YoshinoBotDeploy**
