# Creative Studio

用于图片与视频创作的本地 macOS 工作台，提供创意生成、event 图、推广图改尺寸、抠图和视频改尺寸等功能。素材与任务保存在本地目录，由用户自行配置 API 密钥。

## 下载

[下载最新版本（GitHub Releases）](https://github.com/zuoyi4sylvia/creative-studio-releases/releases/latest)

- 系统要求：Apple Silicon（M 系列）Mac，macOS 14 或更高版本。暂不支持 Intel Mac。
- 首次安装：下载 DMG，打开后将 Creative Studio 拖入 Applications，再从 Applications 启动。不要直接在 DMG 中运行。
- 旧版用户：手动安装 2.2.0 一次，此后可以从应用菜单「检查更新…」或「设置 → 应用更新」获取新版。

## 应用内更新

使用 Sparkle 2，每天自动检查 GitHub Releases，也可以关闭自动检查。发现新版后由用户选择是否下载安装。生成任务运行期间会延后安装；更新前保存未提交的输入，重新打开后恢复。更新包与更新源采用 Ed25519 签名校验，发布附件附带 SHA256SUMS.txt。

## 发行状态

当前版本尚未使用 Apple Developer ID 签名或经过 Apple 公证，首次安装可能遇到 macOS 安全提示或被阻止。正式推广发行前需要补上 Apple 签名与公证。更新签名不能替代 Apple 公证。

本仓库用于发布安装包和更新信息，不包含应用源码、用户 API 密钥、参考素材、工作区或生成记录。GitHub 自动提供的 Source code 附件仅包含此发布仓库的说明文件，不是应用安装包。
