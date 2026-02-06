# SaltyFish咸鱼云VPS选购指南：CN2 GIA/9929优化线路，低至$6.5/月起

说到海外VPS，搞过建站或者折腾过网络的朋友多少都踩过坑——买回来一看，晚高峰卡成PPT，ping值高得让人怀疑人生，花了钱还受罪。

SaltyFish（咸鱼云）这家商家，名字听着挺佛系，但做的事一点不佛系。2020年左右成立，注册主体是 SnapStack Limited，背后是国人团队在运营。它家主打的卖点很明确：**给中国大陆用户提供回程优化线路的海外VPS**。目前提供德国法兰克福、美国圣何塞、荷兰阿姆斯特丹三个主要机房，托管在Equinix数据中心，线路上覆盖了电信CN2 GIA和联通AS9929/AS10099两大优质回程网络。

你可能会问，市面上VPS商家那么多，咸鱼云有什么不一样？简单说三个字：**线路好**。他们家不搞什么普通直连糊弄人，全线产品要么CN2 GIA，要么联通9929，都是圈内公认的"晚高峰也能跑满"的优质线路。对国内用户来说，这就是花同样的钱，体验完全不同的网络质量。

<img width="2772" height="1561" alt="image" src="https://github.com/user-attachments/assets/997e4e27-5704-4972-a2e1-958177310986" />

---

## 咸鱼云产品线一览

在正式看价格之前，先理清一个概念。咸鱼云把自家产品分成了两大系列：

**Premium Network** —— 三网回程走电信CN2 GIA。CN2 GIA是中国电信的顶级国际线路，延迟低、丢包少，在晚高峰时段表现依然稳定，堪称回国线路的"天花板"。

**Elite Network** —— 三网回程走联通AS10099/AS9929（也就是圈内常说的CUG/CUII 9929）。这条线路是联通的精品网络，可以理解为联通版的"CN2 GIA"，延迟和稳定性同样非常能打。

两种线路各有千秋：CN2 GIA覆盖面更广、三网兼容性好；9929在某些地区联通用户体验甚至更优，而且价格上往往还便宜一点点。具体选哪个，看你自己的运营商和实际需求。

---

## 德国法兰克福机房

法兰克福是咸鱼云的欧洲主力节点，也是他们产品线最丰富的一个机房。适合需要欧洲IP的用户，不管是建站、跑业务还是解锁欧区流媒体，都是不错的选择。

### Premium Network（CN2 GIA线路）

法兰克福CN2 GIA系列采用Intel系列CPU，三网回程电信CN2 GIA，带宽高达2.5Gbps，这个带宽在CN2 GIA线路里算相当大方了。

| 套餐 | CPU | 内存 | SSD | 流量/带宽 | 月付价格 | 购买 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| fra.p1.mini | 1核 | 1GB | 15GB | 1TB / 2.5Gbps | $7.8/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=14) |
| fra.p1.micro | 1核 | 2GB | 20GB | 2TB / 2.5Gbps | $15/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=14) |
| fra.p1.medium | 2核 | 4GB | 40GB | 4TB / 2.5Gbps | $30/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=14) |

从digvps等测评站点的信息来看，法兰克福CN2 GIA系列此前有过8.5折的促销优惠码 `FRA-P-7HRV36BYYN`（季付及以上周期可用），不过优惠码的有效期会随活动变化，建议下单时实际测试是否仍可使用。

### Elite Network（联通9929线路）

法兰克福的9929线路分为Edge1和Edge2两个区域。Edge1采用AMD EPYC CPU、500Mbps带宽；Edge2采用AMD Ryzen CPU、300Mbps带宽。两者价格一样，主要区别在硬件平台和带宽大小。需要注意的是，Edge区域网络延迟相比核心区域会略高一些，并且Elite Network产品不支持24小时无理由退款。

| 套餐 | CPU | 内存 | SSD | 流量/带宽 | 月付价格 | 购买 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| fra.e1/e2.mini | 1核 | 1GB | 15GB | 1TB / 300~500Mbps | $7.5/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=25) |
| fra.e1/e2.micro | 1核 | 2GB | 20GB | 1.8TB / 300~500Mbps | $14.5/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=25) |
| fra.e1.medium | 2核 | 4GB | 40GB | 4TB / 500Mbps | $25/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=25) |

法兰克福Elite Network此前的促销优惠码包括 `FRA-E1-WBR8UPXQP8`（8.2折）、`FRA-E2-CHJ685KO6U`（8.5折），同样建议下单时实测有效性。

---

## 美国圣何塞机房

圣何塞是咸鱼云的美西节点，也是国内用户最常选的机房。美西到国内的物理距离更近，延迟天然比欧洲节点低不少——实测CN2 GIA线路全国平均延迟在140~160ms左右，联通9929甚至能跑到130ms，日常使用体验相当丝滑。

### Premium Network（CN2 GIA线路）

圣何塞CN2 GIA系列默认1Gbps带宽，三网回程电信CN2 GIA，测评数据显示电信双程CN2 GIA、联通和移动去程也走优化链路（AS9929），回程统一CN2 GIA。

| 套餐 | CPU | 内存 | SSD | 流量/带宽 | 月付价格 | 购买 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| sjc.p1.mini | 1核 | 1GB | 15GB | 1TB / 1Gbps | $6.8/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=15) |
| sjc.p1.micro | 1核 | 2GB | 20GB | 2TB / 1Gbps | $14/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=15) |
| sjc.p1.medium | 2核 | 4GB | 30GB | 4TB / 1Gbps | $28/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=15) |

圣何塞CN2 GIA此前有7.9折循环优惠码 `SJC-P-GGM2R2O5HG`，属于春季促销活动的延续。这个优惠码在多个评测站点都有提及，下单时可以尝试使用。

### Elite Network（联通9929线路）

圣何塞9929线路同样是1Gbps带宽，而且流量给得还稍微多一点（最低配1.2TB vs CN2 GIA的1TB），价格也略低。对联通用户来说性价比很高。

| 套餐 | CPU | 内存 | SSD | 流量/带宽 | 月付价格 | 购买 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| sjc.e1.mini | 1核 | 1GB | 15GB | 1.2TB / 1Gbps | $6.5/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=18) |
| sjc.e1.micro | 1核 | 2GB | 20GB | 2.4TB / 1Gbps | $13.5/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=18) |
| sjc.e1.medium | 2核 | 4GB | 30GB | 4TB / 1Gbps | $29/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=18) |

圣何塞Elite Network此前也有7.9折优惠码 `SJC-E-V46OI8BJIV`，实际是否有效请在购买页面验证。

---

## 荷兰阿姆斯特丹机房

阿姆斯特丹目前只提供Premium Network（CN2 GIA）线路，2.5Gbps大带宽是亮点。不过这个机房到国内的延迟比法兰克福还要高一些（实测大约180~200ms），适合对IP地理位置有特定要求的用户。

值得注意的是，阿姆斯特丹最低配套餐起步价仅$17.4/季（约合$5.8/月），这在CN2 GIA线路中算是相当有竞争力的价格了。

| 套餐 | CPU | 内存 | SSD | 流量/带宽 | 价格 | 购买 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| ams.p1.mini | 1核 | 1GB | 15GB | 1TB / 2.5Gbps | $17.4/季 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=22) |
| ams.p1.micro | 1核 | 2GB | 20GB | 2TB / 2.5Gbps | $11.8/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=22) |
| ams.p1.medium | 2核 | 4GB | 30GB | 4TB / 2.5Gbps | $23.6/月 |  [点击选购](https://portal.saltyfish.io/aff.php?aff=551&gid=22) |

阿姆斯特丹系列此前有8.5折优惠码 `AMS-P-K62Y2AQ4QT`（nano套餐除外），感兴趣的可以试试。

---

## 美国圣何塞 Standard Network（联通4837线路）

除了上面的"高端线路"，咸鱼云还有一条入门级的Standard Network，走联通AS4837回程。4837是联通的普通国际出口，没有CN2 GIA和9929那么"尊贵"，但胜在价格便宜、带宽给得大。根据此前的促销活动，这个系列年付低至199.99元，配合2.5Gbps的大带宽，跑跑下载、做做流量转发还是很香的。

不过Standard Network产品的库存和促销节奏比较随缘，感兴趣的话可以 👉 [去咸鱼云官网看看](https://portal.saltyfish.io/aff.php?aff=551) 当前是否有货。

---

## 实测体验怎么样？

根据各测评站点的数据汇总，咸鱼云的网络表现大致是这样的：

**美国圣何塞CN2 GIA**：全国电信平均延迟约154ms，联通约177ms，移动约197ms。电信用户体验最佳，双程CN2 GIA，晚高峰也能保持稳定。Speedtest跑速理想，日常建站、远程操作都很流畅。Geekbench 6单核跑分约690分，CPU性能中规中矩，跑个人博客和轻量应用没问题。

**德国法兰克福CN2 GIA**：国内ping值大约在160~180ms，比美西高一些但在欧洲节点里已经算不错了。硬件方面部分机型用的是AMD EPYC平台，性能表现靠谱。

**流媒体解锁**：测评显示YouTube Premium可以正常解锁，但Netflix和Disney+对IP的检测比较严格，不一定所有IP段都能解锁。如果流媒体是刚需，建议开通后实际测试一下。

咸鱼云全线产品都是KVM虚拟化、SSD硬盘，支持一键安装常见Linux系统。对于建站、搭博客、跑轻量服务来说，配置完全够用。

---

## 关于付款和售后

咸鱼云支持**支付宝**和**PayPal**付款，对国内用户非常友好。控制面板虽然是英文界面，但操作逻辑和常见的WHMCS面板一样，用过类似产品的话上手没什么门槛。

售后方面，Premium Network产品支持24小时无理由退款（有一些限制条件，比如使用流量不超过15GB、没有滥用行为等），这一点给了用户一个"先试试看"的机会。不过Elite Network系列不支持24小时退款，购买前最好先用他们提供的测试IP跑跑看合不合适。

**测试IP汇总：**
- 圣何塞CN2 GIA：185.218.6.30
- 圣何塞9929：185.218.7.77
- 法兰克福CN2 GIA：31.25.88.20
- 法兰克福9929：38.59.230.254
- 阿姆斯特丹CN2 GIA：185.212.60.5

另外，他们还提供了一个Looking Glass测试页面：https://lg.saltyfish.io/ ，可以在线进行ping、traceroute等测试，买之前跑一遍心里有数。

---

## 怎么选？给你几个参考

**预算有限、追求性价比**：圣何塞Elite Network（9929线路），$6.5/月起，1Gbps带宽+1.2TB流量，对联通用户尤其友好。

**电信用户、追求最低延迟**：圣何塞Premium Network（CN2 GIA），$6.8/月起，电信双程CN2 GIA，延迟最稳。

**需要欧洲IP、大带宽**：法兰克福Premium Network，2.5Gbps带宽，CN2 GIA回程。

**最便宜的CN2 GIA入门**：阿姆斯特丹Premium Network，$17.4/季起步，折合每月不到6美元。

**跑流量、不在乎线路等级**：等Standard Network（4837线路）促销的时候入手，年付200元左右，2.5Gbps大带宽。

