# Codex LED Widget

## 中文说明

Codex LED Widget 是一个 Windows 漂亮的桌面透明质感高颜值悬浮小组件，用于显示本机 Codex 剩余额度。

界面采用液态玻璃质感，并通过红绿灯状态快速展示额度情况。
![Codex LED Widget Screenshot](assets/screenshot.png)
## 功能

- 液态玻璃质感界面
- 红绿灯额度状态
  - 绿色：剩余额度大于等于 10%
  - 黄色：剩余额度小于 10% 且大于 0
  - 红色：剩余额度为 0
- 支持中文 / English 切换
- 支持置顶 / 取消置顶
- 自动刷新额度
- 到重置时间后自动重新读取额度

## 使用方法

1. 下载 Release 中的 exe 文件
2. 确保本机已经安装并登录 Codex
3. 双击运行 exe
4. 如果 Windows 提示未知发布者，请点击“更多信息”，然后选择“仍要运行”

## 隐私说明

- 本工具使用本机 Codex 登录状态读取额度信息
- 不会读取、保存或显示你的认证 Token
- 剩余额度根据 Codex 返回的 `usedPercent` 字段计算

## English

Codex LED Widget is a Windows floating desktop widget for showing your local Codex remaining usage quota.

The interface uses a liquid glass style and displays quota status with a traffic-light indicator.

## Features

- Liquid glass style interface
- Traffic-light quota status
  - Green: remaining quota is 10% or higher
  - Yellow: remaining quota is below 10% and above 0
  - Red: remaining quota is 0
- Chinese / English language switch
- Pin / unpin always-on-top
- Automatic quota refresh
- Automatically refreshes again after the quota reset time

## How to Use

1. Download the exe file from Releases
2. Make sure Codex is installed and signed in on your computer
3. Double-click the exe to run it
4. If Windows shows an unknown publisher warning, click “More info”, then choose “Run anyway”

## Privacy

- This tool uses your existing local Codex sign-in state to read quota information
- It does not read, store, or display your authentication tokens
- The remaining quota is calculated from Codex’s `usedPercent` field
