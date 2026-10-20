# 穿云箭下载（Aero Downloader）隐私政策

最后更新：2026-10-20

穿云箭下载（下称"本扩展"）是一款浏览器多线程下载扩展，由开发者"罗根"制作。我们非常重视你的隐私。本扩展的设计原则是：**一切数据都留在你自己的电脑上。**

## 一、我们不收集任何用户数据

本扩展不收集、不上传任何用于远端处理的用户数据：没有账号体系、没有统计埋点、没有广告 SDK、不与任何第三方共享或出售数据。扩展不会读取你的浏览历史、网页内容、位置信息、通讯录或任何个人身份信息。

## 二、数据只保存在你的设备上

1. 扩展设置（下载拦截模式、界面语言等）保存在浏览器本地的扩展存储中；
2. 下载任务与历史记录保存在浏览器本地的 IndexedDB 数据库中；
3. 下载过程中的文件分片暂存于本机 IndexedDB/OPFS，合并完成后保存为你指定的本地文件。

以上数据可随时通过卸载本扩展或在扩展面板中删除历史记录来清除。

## 三、网络请求

本扩展仅在你主动发起下载时，向你要下载的目标文件服务器发送 HTTP/HTTPS 请求以下载文件内容；除此之外不会向任何服务器发送任何请求。

## 四、权限用途说明

- 下载（downloads）：保存下载的文件、管理下载任务、拦截并接管浏览器下载；
- 存储（storage）/ 无限存储（unlimitedStorage）：在本地保存设置与任务历史、暂存大文件分片；
- 通知（notifications）：下载完成或失败时向你发送提醒；
- 右键菜单（contextMenus）：提供"用穿云箭下载"右键入口；
- 主机权限（http/https）：向你要下载的文件服务器发起下载请求。

## 五、未成年人

本扩展不收集任何用户数据，因此不涉及收集未成年人信息的问题。

## 六、联系方式

如有隐私相关问题，请通过 Microsoft Edge 加载项商店页面上的"开发者支持"联系方式与我们联系。

---

## English Summary

**Privacy Policy — Aero Downloader (穿云箭下载) Browser Extension**

This extension does **not** collect, transmit, or share any user data. There are no accounts, no analytics, no advertising SDKs, and no third-party data sharing.

All data (extension settings, download task history, temporary file chunks) is stored **locally on your device only**. You can erase it at any time by uninstalling the extension or deleting history within the extension panel.

The only network traffic the extension generates is the HTTP/HTTPS requests it makes **on your explicit action** to the target file server you are downloading from, in order to download the file itself.

Permissions are used solely for: managing and saving downloads (downloads), local settings & task storage (storage / unlimitedStorage), completion notifications (notifications), the right-click "Download with Aero Downloader" menu (contextMenus), and requesting file data from download servers (host permissions).

Contact: via the developer support link on the Microsoft Edge Add-ons store listing.
