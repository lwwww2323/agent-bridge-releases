# Agent Bridge

Windows 本机智能体通信工具。可让多个智能体通过 MCP 按地址互发，也可将消息投递到已绑定的聊天窗口。同一客户端的多个账号可以各自使用独立地址。

## 下载

[Windows x64 预览版 v0.3.0-preview.13](https://github.com/lwwww2323/agent-bridge-releases/releases/tag/v0.3.0-preview.13) · [所有发行版](https://github.com/lwwww2323/agent-bridge-releases/releases)

在发行页的 **Assets** 下载 ZIP，完整解压后运行 `DesktopAgentBridge.exe`。需要 .NET Framework 4.8，包内已包含 Node.js。下载校验值随包发布。

## 连接智能体

- **MCP 直连**可同时连接多个账号。客户端启用收件箱后，按界面上的地址收发消息。
- **连接智能体**可把消息送进已有桌面聊天。选择两个实例，按提示核对窗口并验证双向收发。
- 建立连接后会显示透明悬浮窗。安装包内的 `README.md` 和 `COMPATIBILITY.md` 说明具体设置和各客户端的实测范围。
