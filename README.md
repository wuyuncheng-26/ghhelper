<h1 align="center">ghhelper</h1>

<h2 align="center">这是一个用来介绍 GitHub 专有名词的项目</h2>

## 目录

[仓库（repository）](#仓库repository)

[SSH](#ssh)

[GPG](#gpg)

### 仓库（repository）
GitHub 中的仓库其实就是项目的意思，里面存放着的是项目代码。
仓库分为公开仓库和私有仓库，公开仓库就是所有人都可以访问的仓库，私有仓库就是只有自己可以访问的仓库。

### SSH
SSH 是 Secure Shell 的缩写，是一种在不安全网络上用于安全远程登录和其他安全网络服务的协议。
比如说你在使用一个不安全的 WiFi 上网，那么你可以使用 SSH 协议来登录到你的服务器上，SSH 让连接更加安全。
由于 SSH 的可靠性，GitHub 和其他代码托管网站都支持使用 SSH 进行代码的克隆与传输。
GitHub 支持使用 SSH 协议与 HTTPS 协议来克隆代码，而 SSH 一般都会比 HTTPS 快。
小贴士：在使用 SSH 克隆 GitHub 上的仓库前，请务必在[这里](https://github.com/settings/keys)添加 SSH 密钥。

### GPG
GPG 是一款开源的非对称密钥加密软件，可以用于加密和解密电子文件以及各种数据。
比如说，你现在有一个文件，你想把它发送给某个人，但是你又不想让别人看到里面的内容。
这时你就就可以用 GPG 加密，然后把加密后的文件发送给他。
如果某个人想打开你的文件，他可以使用你提供的公钥来解密文件。
小贴士：在使用 GPG 提交代码到 GitHub 上的仓库前，请务必在[这里](https://github.com/settings/keys)设置好你的 GPG 密钥。