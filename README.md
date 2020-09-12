## react-native-webrtc-server
- 这是一台信令服务器（signaling server）, 端口 4443
- 此服务是（加入房间工作模式，需要 P2P 请修改 app.js 即可）

![walFDx](https://s1.ax1x.com/2020/09/12/walFDx.png)

![wanWYd](https://s1.ax1x.com/2020/09/12/wanWYd.png)

## 开始使用

1. `npm install`
2. `npm start`  或  `node app.js`
3. `流媒体服务器地址，请修改 index.html to 34 line`

## 网页访问
http://127.0.0.1:4443/

`请使用最新版谷歌访问，127.0.0.1（环回地址）因为 W3C 2019 新规，启用媒体需要在https下的域名，屏蔽了 192.168.*.* 路由地址。导致媒体 API 没被注册问题。`

`先启用：摄像头麦克风 或 屏幕分享，然后加入房间即可`

其中包含文件（流媒体服务器部署【STUN、TURN】）, 需要请参考 kurento 开源服务器。
