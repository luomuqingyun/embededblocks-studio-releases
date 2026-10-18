# EmbedBlocks Studio 安装包

这个仓库只用来发布 EmbedBlocks Studio 的安装包，不包含源代码。

## 怎么下载

打开 [Releases 页面](https://github.com/luomuqingyun/embedblocks-studio-releases/releases)，选择版本，在附件里下载需要的安装包。

## 怎么核对

每个版本的附件里都有一个以 `SHA256SUMS` 开头的校验文件，记录了每个安装包的 SHA-256。下载后可以核对：

- Windows（PowerShell）：`Get-FileHash -Algorithm SHA256 <安装包文件名>`，把输出的哈希与校验文件里的值对比。
- Linux / macOS：在下载目录里运行 `sha256sum -c <校验文件名>`。

## 版本说明

标记为 Pre-release 的版本是测试版，可能还有问题。
