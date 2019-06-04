# ioa-socket

基于socket.io的webSocket服务端，兼容controller、middleware。

## 备注

ioa-socket尝试抹平http和webSocket协议之间的差异，用于资源共享。

实际受限于持久化与非持久化连接的差异，如果强行构建标准化会削弱webSocket的优势，有些得不偿失。

目前，暂时使用标准化与差异化api并存的方案。

### Install

```
npm i @ioa/socket
```