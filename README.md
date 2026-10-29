# ywork-releases

Y-Work 桌面端（`gitxm/yrec-login-app`）的安装包与自动更新版本源，只放发布产物，不放源码。

- 每个 `v*` Release 由 `gitxm/yrec-login-app` 的 tag 流水线同步上传。
- 资产命名：`ywork-<版本>-mac-universal.dmg`、`ywork-<版本>-mac-universal.zip`、`ywork-<版本>-win-x64.exe`，另有 `latest.json`（版本号与各文件 SHA-256）。
- 桌面端匿名读取本仓的最新 Release，下载前用资产摘要或 `latest.json` 校验 SHA-256。
- 普通用户请从 https://work.ixiamu.com/downloads/ 下载。
