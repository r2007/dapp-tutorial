# 用NVM安装Node.js 6.x LTS

## 0 - 先决条件
```
$ sudo apt-get update
$ sudo apt-get install build-essential libssl-dev
$ sudo apt-get install git curl
```
## 1 - 安装NVM
2选1:
```
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
```
或者:
```
$ wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
```
检查是否成功
```
$ command -v nvm
nvm
```
## 2 - 安装Node.js 6.x
```
$ nvm install 6
```
检查版本
```
$ node -v
v6.13.0
```
# 安装truffle
```
npm install -g truffle
```
验证
```
$ truffle version
Truffle v4.1.0 (core: 4.1.0)
Solidity v0.4.19 (solc-js)
```
# 安装以太本地测试链
在浏览器打开[http://truffleframework.com/ganache](http://truffleframework.com/ganache)页面，点击下载按钮。下载完毕后运行`chmod a+x 刚刚下载的文件`,确保有可以执行的权限。然后可以直接在文件管理器双击运行，也可以在控制台运行`./下载的文件`。
