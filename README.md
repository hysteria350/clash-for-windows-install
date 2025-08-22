# Windows 平台 Clash for Windows 安装与使用
## **简介**

Clash 是一个使用 Go 语言编写，基于规则的跨平台代理软件核心程序。 Clash for Windows 是运行在 Windows 上的一图形化 Clash 分支。通过 Clash API 来配置和控制 Clash 核心程序，便于用户可视化操作和使用。

## **下载安装**

可以访问 Github 地址进行下载：[https://github.com/Fndroid/clash_for_windows_pkg/releases](https://github.com/Fndroid/clash_for_windows_pkg/releases)

若使用 Chrome 浏览器下载 exe 文件，可能会提示不安全，请忽略此提示。

由于 Clash for Windows 没有任何有效的数字签名，因此 SmartScreen 可能会弹出提示，请点击"更多信息"，然后选择"仍要运行"。

## **添加订阅**

先进行 [订阅购买](https://shortlink181.github.io/1) ，获取到订阅链接。订阅链接位于：仪表盘 > 一键订阅 , 然后复制订阅地址或者扫描二维码订阅。

打开 Clash for Windows 应用程序，在左侧的标签页中选择 Profiles，在顶部输入您的 **Clash 订阅链接**，然后点击 Download 按钮。

![1-订阅.png](https://i.loli.net/2019/11/13/r4fvMDe82shTRlI.png)

Clash for Windows 会自动拉取配置文件进行更新，如果一切顺利，你应当可以看到绿色提示信息「Success!」，并且可以看到一个新增的配置文件：

![2-订阅成功.png](https://i.loli.net/2019/11/13/TrBjWdKkcPG6NfQ.png)

点击新增的配置文件来切换到该配置，然后点击「Proxies」标签页来切换接入点，将顶部的出站模式选择为「Rule」。 此模式下你的网络访问请求将通过 Clash for Winows 进行**分流处理**。

![3-选择模式.png](https://i.loli.net/2019/11/13/yNwHQ5oxO9L7Zb2.png)

在「Proxy」策略组中选择所想要使用的接入点。Proxy 策略组是用于访问国际网络的默认策略，在不进行其他修改的情况下，所有国际网络的访问都通过 Proxy 策略组中选择的接入点进行。

图中所示的策略组是编者根据实际需求配置的，故略有不同爱国。请以自己的实际情况为准。

返回到「General」部分，将「System Proxy」的开关更改为绿色或「On」状态即可开始使用。此外，如果您需要让 Clash for Windows 开机自启，可以将「Start with Windows」也更改为绿色或「On」。

![4-打开代理.png](https://i.loli.net/2019/11/13/1zTZU385nsDYJfX.png)
