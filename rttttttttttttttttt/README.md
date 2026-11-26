# 朋友圈高仿版 Android APK 工程

本工程已将你最新版的高仿朋友圈（含 320 位随机机器人引擎、图文九宫格、本地视频选择与定位功能）封装为完整原生 Android WebView App。

## 生成可安装 APK 的两种方式

### 方式一：电脑安装 Android Studio（推荐）
1. 解压本压缩包，用 **Android Studio** 打开目录。
2. 等待 Gradle 自动同步完成。
3. 点击顶部菜单 **Build -> Build Bundle(s) / APK(s) -> Build APK(s)**。
4. 构建完成后，在 `app/build/outputs/apk/debug/app-debug.apk` 即可拿到安装包，传到安卓手机安装即可。

### 方式二：电脑没装 Android Studio（GitHub 云端免费自动出包）
1. 在 GitHub 新建一个仓库，把解压后的全部文件上传到仓库根目录。
2. 打开仓库顶部的 **Actions** 页面，运行 **Build Android APK** 工作流。
3. 等待约 1~2 分钟，在页面底部 **Artifacts** 处直接下载 `WeChatMoments-APK` 即可得到 `app-debug.apk`。
