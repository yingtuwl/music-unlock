# Music Unlock  音乐解锁 (React)

⚠️ 手机端浏览器支持有限，请使用最新版本的 Chrome 或 Firefox 官方浏览器。

## 支持的格式

- [x] QQ 音乐 QMCv1 (`.qmc3` / `.qmcflac` 等)
- [x] QQ 音乐 QMCv2
  - PC 客户端 (`.mflac` / `.mgg` 等) [^qm-key-pc]
  - 安卓客户端 (`.mflac0` / `.mgg1` / `.mggl` 等) [^qm-key-android]
  - iOS 客户端 (`.mgalaxy` 等) [^qm-key-ios]
  - Mac 客户端 (`.mflach` 等) [^qm-key-mac]
- [x] 网易云音乐 (`.ncm`)
- [x] 虾米音乐 (`.xm`)
- [x] 酷我音乐 (`.kwm`)
- [x] 酷狗音乐 (`.kgm` / `.vpr` / `.kgg`)
  - PC / 安卓客户端的 `kgg` 文件需要提供密钥数据库。
- [x] 喜马拉雅 (`.x2m` / `.x3m` / `.xm`)
- [x] 咪咕音乐格式 (`.mg3d`)
- [x] 蜻蜓 FM (`.qta`)

[^qm-key-pc]: PC 客户端仅支持 v19.43 或更低版本。

[^qm-key-android]: 需要获取超级管理员权限后提取密钥数据库，并导入后使用。

[^qm-key-ios]: 需要越狱获取密钥数据库，或对设备进行完整备份后提取密钥数据库，并导入后使用。

[^qm-key-mac]: 需要导入密钥数据库。
