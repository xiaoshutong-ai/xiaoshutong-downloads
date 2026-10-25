# 小书童 Core Android — 正式公开下载

**当前正式版：v0.1.2（2026-10-25）**。正式发布后根据实际使用反馈持续改进。

- [正式发布页及更新记录](https://github.com/xiaoshutong-ai/xiaoshutong-downloads/releases/tag/core-android-v0.1.2-20261025)
- [直接下载 Android APK（约 403 MB）](https://github.com/xiaoshutong-ai/xiaoshutong-downloads/releases/download/core-android-v0.1.2-20261025/xiaoshutong-core-android-v0.1.2.apk)
- [第三方许可证、署名及对应源码](https://github.com/xiaoshutong-ai/xiaoshutong-downloads/releases/download/core-android-v0.1.2-20261025/xiaoshutong-core-android-v0.1.2-thirdparty-notices.zip)
- [公开文件 SHA-256 清单](https://github.com/xiaoshutong-ai/xiaoshutong-downloads/releases/download/core-android-v0.1.2-20261025/SHA256SUMS.txt)

正式版 Android 包名：cn.xiaoshutong.child，版本号 0.1.2（versionCode 1），Android 8.0+ ARM64。已安装同证书正式版可保留数据更新；历史 Alpha 与正式版包名不同，不能互相覆盖。

APK SHA-256：bf97a4f60bad3da2620dd5093c21e10f75f941ad00c9bb29e09c8fdb5664dfd1

**使用须知：** 由家长协助安装，需要已有授权的家长账号才能进入相关学习功能。公开下载不等于自动开通账号或付费权益。首次发布可能有缺陷，请反馈至 xiaoshutong2026@foxmail.com，不要在公开 Issue 中披露密码、验证码或儿童原始音视频。

官网：https://xiaoshutong.xyz/

此处是**公开 APK 与许可证分发仓库**。正式业务工程仓库与源代码继续保持私有；这里不存储签名密钥、个人账号资料或儿童学习数据。

---

以下旧版 Alpha 说明仅作历史留存，不代表当前正式发行版本。

## 历史存档：Alpha 内部测试安装包

当前版本：`0.1.2-alpha-account.3`（versionCode 5），Android 包名：`cn.xiaoshutong.child.alpha`。

此安装包用于已授权的内部开发测试，提供账号注册、邮箱验证、登录、找回密码和文字对话。账号支持多部手机登录；实际可用功能取决于账号已开通的权限。

## 安装与更新

1. 从 [GitHub Releases](https://github.com/xiaoshutong-ai/xiaoshutong-downloads/releases/tag/alpha-account-20261011.3) 下载本次附件 `app-alpha-account-hardened-20261011.apk`。
2. 在 Android 手机上打开下载文件，按系统提示允许本次安装。
3. 已安装同名 Alpha 的手机可直接更新。请保留现有应用数据，无需卸载。
4. 打开“小书童 Alpha”，用自己的小书童账号登录。新账号请完成邮箱验证。
5. 进入“内部测试”→“开始文字交流”，发送消息。

忘记密码时，请在登录页选择“忘记密码？”，用自己的账号邮箱收取验证码，并在 App 内输入验证码和两次新密码。密码规则以 App 页面说明为准。密码、验证码与 API Key 不应发给他人。

## 文件校验

文件大小：196,902,398 字节（约 188 MiB）。

SHA-256：

```text
c549a281fe3addc0abc7fa8dc2b1814235d72b6d00d09e9df8ddaf664d2b2e4e
```

## 本次更新

- 注册时确认两次密码，并显示与现有账号服务一致的密码规则。
- 支持重新发送注册验证邮件。
- 增加 App 内邮箱验证码找回密码流程。
- 根据原生账号服务的限流响应提示稍后重试。
- 关闭调试能力和调试测试入口，启用代码混淆与资源压缩。
- 沿用已有安装签名，可覆盖更新，保留现有应用数据。

安装包下载与账号授权分别管理。获得安装包不代表获得业务访问权限。

此仓库仅用于安装包、校验值和安装说明的公开分发。服务端源码、模型服务凭据、数据库配置、签名私钥和混淆映射不在这里发布。公开 APK 中的界面代码和公开 API 地址可能被分析，代码混淆不能保证客户端代码保密；模型调用与账号权限验证由服务端执行。

本次为内部测试预发布，支持文字交流。此前同账号在 vivo 与 Note9 的实际对话已由测试者确认；本加固版本在 Note9 完成登录、实际回复、全新邮箱注册收件与验证、找回密码页面检查。版本验收不代表语音功能或面向真实儿童的业务上线验收。
