# MOSEC-NODE-PLUGIN

用于检测 node 项目的第三方依赖组件是否存在安全漏洞。

该项目是基于 [snyk/resolve-deps](https://github.com/snyk/resolve-deps.git) 的二次开发。

## 关于我们

Website：https://security.immomo.com

WeChat:

<img src="https://momo-mmsrc.oss-cn-hangzhou.aliyuncs.com/img-1c96a083-7392-3b72-8aec-bad201a6abab.jpeg" width="200" hegiht="200" align="center" /><br>

## 版本要求

npm >= 5.2.0

## 使用

首先运行 [MOSEC-X-PLUGIN Backend](https://github.com/momosecurity/mosec-x-plugin-backend.git)

#### 无需安装即可使用
```
> cd your_node_project/
> npx github:momosecurity/mosec-node-plugin \
  --endpoint http://127.0.0.1:9000/api/plugin \ 
  --only-provenance
```
