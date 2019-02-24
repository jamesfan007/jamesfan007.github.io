---
layout: default
title: Peer的网络架构
---

## Peer的网络架构

![peer](./docs/img/peer.jpg)  
- **IPC是Peer真正物理实体设备。**  
  固定在家或公司，24小时提供服务。可以通过人脸识别、实时可视通话等方式对使用者身份认证和绑定；位置固定，可以通过IP地址和周边电磁指纹等确定和追溯地理位置；通过peer上的公开数据，与其他人的交易交流记录，可以确定使用者的朋友圈或工作圈。也就是说，可以通过peer确定对方是谁、在哪里、干什么的。  
- **NVR或NAS扩展私人存储空间。**  
  数据由IPC提供加密和分布式存储管理。NVR/NAS的重要数据加密备份在第三方的云存储空间。数据自动同步，IPC看到的是同一份数据。有效对抗数据的灭失或窃取的风险。第三方的云存储服务商无法查看peer数据。  
- **手机是进行交流交易的操作终端。**  
  身份认证由IPC处理，信息存储在IPC，因为手机有遗失风险，被黑客入侵风险。IPC的软件功能可以比较单一，不会安装外来程序，可以将安全性提高。目前广泛使用的短信身份验证，都是假设手机使用者就是本人，假设手机卡没有被盗用，风险较高。  
- **第三方云服务托管数据和缓冲服务。**  
  若使用者有大量数据需要分享，并拥有大量粉丝，则可以将分享的数据托管在第三方云服务器上，数据的所有权和访问权限的管理，仍然由peer处理。访问者的Peer要先与被访问者的Peer握手。Peer与云服务只是一个负载均衡关系，没有依附关系。Peer的云服务对其它Peer的访问是透明和无感的。  

```
人人平等，世界和平
```

[回到主页](http://jamesfan007.github.io/)

---

#### 原创声明：

##### 所有文章均为原创。 <br/> 如果引用，必标明出处；若为转贴，定附上链接。

###### 作者：James Van <br/> 链接：http://jamesfan007.github.io/ <br/> 代码：https://github.com/jamesfan007/jamesfan007.github.io <br/> 联系：mail:[jamesfan007@hotmail.com]  <br/> &emsp;&emsp;&emsp;wechat:[CleverDogMaster]

---