# 轩轩音乐 · 发布仓库

本仓库只存放「应用内升级」与「音源订阅」所需的配置文件和安装包，由 release-repo/publish.ps1 自动发布。

## 应用端地址（固定不变）

| 用途 | 地址（应用内自动逐个尝试） |
| --- | --- |
| 版本清单 | https://ghfast.top/https://raw.githubusercontent.com/sushiguo/xuanxuan-release/main/update.json |
| 音源订阅 | https://ghfast.top/https://raw.githubusercontent.com/sushiguo/xuanxuan-release/main/sources.json |
| APK 直链 | https://ghfast.top/https://github.com/sushiguo/xuanxuan-release/releases/latest/download/xuanxuan-music.apk |

> 国内直连 raw.githubusercontent.com / github.com 会超时；备用 gh-proxy.com、jsDelivr、GitHub 直连。

## 设备点击升级

浏览器打开即下载 APK（Content-Type: application/vnd.android.package-archive），下载完点通知即可覆盖升级、保留数据：

https://gh-proxy.com/https://github.com/sushiguo/xuanxuan-release/releases/latest/download/xuanxuan-music.apk

备用镜像（同一文件）：

https://ghfast.top/https://github.com/sushiguo/xuanxuan-release/releases/latest/download/xuanxuan-music.apk

## 应用内升级

设置 → 检查更新 → 拉取 update.json → 与本地 versionCode 比较 → 下载 APK → 系统安装器。
首次安装需在系统设置里允许本应用「安装未知应用」。

## 音源订阅

管理源 → 从仓库同步音源 → 二选一：

- 新增为自定义源：仓库源只补位，不覆盖安装包内置源；
- 使用内置源：清掉自定义/禁用记录，回到本版本内置配置。

## 当前版本

- versionName: 6.1.0.610282255
- versionCode: 610282255
- 更新时间: 2026-10-28 23:02:57