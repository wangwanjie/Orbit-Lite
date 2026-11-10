<p align="center">
  <img src="assets/icon-256.png" width="128" height="128" alt="Orbit 图标">
</p>

<h1 align="center">Orbit（跨平台版）</h1>

<p align="center">
  同时支持 <b>Windows 10/11</b> 与 <b>macOS 13+</b> 的效率工具合集：用一个常驻后台的轻量进程，提供启动器、剪贴板、窗口控制、截图与系统维护。
</p>

<p align="center">
  <a href="https://wangwanjie.github.io/Orbit-RS/">主页</a> ·
  <a href="https://github.com/wangwanjie/Orbit-RS/releases/latest">下载</a> ·
  <a href="https://github.com/wangwanjie/Orbit-RS/issues">反馈</a>
</p>

本仓库只存放安装包、在线更新清单与主页，不含源码。macOS 原生版见 [wangwanjie/Orbit](https://github.com/wangwanjie/Orbit)。

## 下载

| 系统 | 下载最新版 | 说明 |
| --- | --- | --- |
| Windows 10 / 11（x64） | [Orbit-Windows-Setup.exe](https://github.com/wangwanjie/Orbit-RS/releases/latest/download/Orbit-Windows-Setup.exe) | 安装界面按系统语言显示简体中文、繁體中文或英文；安装到当前用户，无需管理员权限 |
| macOS 13 或更高（Apple 芯片与 Intel 通用） | [Orbit-macOS.dmg](https://github.com/wangwanjie/Orbit-RS/releases/latest/download/Orbit-macOS.dmg) | 已经过 Apple 公证；打开 DMG，把 Orbit 拖进「应用程序」 |

历史版本见 [Releases](https://github.com/wangwanjie/Orbit-RS/releases)。

## 在线更新

Orbit 内置在线更新：默认每天检查一次 [`latest.json`](latest.json)，发现新版本时在「控制中心 › 通用 › 更新」提示，点击「安装并重启」即可完成更新；也可以随时手动检查，或关闭自动检查。
每个更新包都用发布者的私钥签名，客户端用内置公钥验签，签名不符的安装包会被拒绝。

## 功能

| 模块 | 主要能力 |
| --- | --- |
| 启动器 | 应用（支持拼音与首字母）、计算器、网页搜索、网址、文件、系统命令、自定义快捷链接、脚本命令、结束进程、编解码 / 二维码 / 翻译工具 |
| 剪贴板 | 记录文本、富文本、图片、文件、链接、颜色；底部卡片面板，搜索、筛选、收藏夹、固定；直接粘贴或粘贴为纯文本 |
| 窗口管理 | 半屏、四分之一、三分之一、最大化、居中、跨显示器等动作，拖到屏幕边缘吸附 |
| 截图 | 区域 / 窗口 / 全屏 / 延时截图，标注、贴图、文字识别 |
| 系统维护 | 刷新 DNS、重建图标缓存等常用维护任务 |

首次启动时的使用向导会带你选择要启用的模块、熟悉常用快捷键并完成系统授权。

## 发布记录

[`releases.json`](releases.json) 记录每个版本的发布时间、说明与安装包，发布说明的 Markdown 原文在 [`release-notes/`](release-notes)。
