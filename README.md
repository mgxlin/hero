
## 概述

本专案用于在 Heroku 上部署 V2Ray WebSocket，在合理使用的程度下，本镜像不会因为大量占用资源而导致封号。

部署完成后，每次启动应用时，运行的 V2Ray 将始终为最新版本

## 部署

### 步骤

> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/mgxlin/hero)Cancel changes

 4. 回到专案首页，点击上面的链接以部署 V2Ray

### 变量

对部署时需设定的变量名称做如下说明。

| 变量 | 默认值 | 说明 |
| :--- | :--- | :--- |
| `ID` | `ad806487-2d26-4636-98b6-ab85cc8521f7` | VMess 用户主 ID，用于身份验证，为 UUID 格式 |
| `WSPATH` | `/` | WebSocket 所使用的 HTTP 协议路径 |
