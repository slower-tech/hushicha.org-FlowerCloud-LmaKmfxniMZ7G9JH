
我们中高端的windows笔记本上都可以看到Dolby音效，TV电视上也有支持Dolby显示选项。


杜比主要有几类：Dolby全景声（也叫Atmos）、Dolby视界（Vision）、杜比影院（Dolby Cinema）


作为OEM厂商，如何获取杜比授权呢？可以看下Dolby官网的申请流程：[如何获取杜比授权许可 \- Dolby Professional](https://github.com)


上面是官方合同的流程了，没啥特别的，只是起步阶段。下面我讲下了解到的杜比合作流程：


先是合同，与杜比签合同时，Dolby全景声、Dolby视界分别需要支付2\.5万美金押金，押金后面可以退回的


需要说明的是，签合同只能是以一级母公司（如果有的话）来签，提供各种证明啥的


签完合同，后面就是杜比认证流程，也可以叫联调阶段。杜比会安排专人对接提供驱动和软件，适配后寄产品到台湾实验室调参数，整个认证测试大概半个月。这个阶段是不需要费用的


后面就是集成设备，杜比会给驱动以及管理App，OEM厂商集成到母盘生产。如果需要试用的话，Windows Store里也可以安装Dolby Access、Dolby Audio


杜比音效 [杜比音效 \- Dolby Professional \- Dolby Professional](https://github.com)，在OEM端集成到PC上，需要安装驱动。比如这台联想天启，音频处理器这里有DolbyAPO SWC Device音频处理驱动：


![](https://img2024.cnblogs.com/blog/685541/202411/685541-20241115180245578-1589436560.jpg)


再说说真正的使用费用，杜比会统一设备生产数量（线上或者其它渠道），单方向告知每年需要缴纳多少专利费用也叫版税，大概1\-2美金一台。


![](https://img2024.cnblogs.com/blog/685541/202411/685541-20241115174440493-1089694758.png)


注意有坑：因为杜比basic原因（下面会讲），一旦与杜比签合同，公司之前所有windows设备也要补缴专利费，这可不是小数字


啥叫杜比basic，这里 [杜比Windows许可计划常见问题 \- Dolby Professional](https://github.com) 有介绍，结合网上其它文章，总结如下：


Dolby Basic是杜比与Windows合作，从Win10开始默认内置的杜比音效（Dolby Audio），它能满足用户对个人视频及优质娱乐的优化期望。通过在 Windows 中提供对杜比音频 （Dolby Audio） 的完全支持，Microsoft 在 Windows 应用程序中为用户提供一致、兼容和高质量的音频/视频体验。


Win10内置杜比Audio音效，Windows版本包含 AC\-3 编解码器，Edge浏览器也支持杜比Audio [Dolby Digital Plus \- Dolby Professional](https://github.com)，也可以见杜比官网新闻：[微软采用杜比音效提升Windows 10的娱乐体验 \| 杜⽐新闻中⼼](https://github.com)。


AC\-3 是一种支持多声道（“环绕声”）音频的音频编解码器，它也被称为杜比数字“Dolby Digital”。


原本，杜比 Windows Basic 如果公司每年生产超过 10万 台设备，只需向杜比支付版税。每年制造不到 10万台设备的 OEM 可以免费获得杜比技术。


而上面申请Dolby全景声、视界，就有坑了，要补杜比Basic的费用。 


针对这个问题最近有个好消息，Win11 24H2不再内置杜比音效，不预装杜比音频解码器： [Media Player 中的编解码器 \- Microsoft 支持](https://github.com)


![](https://img2024.cnblogs.com/blog/685541/202411/685541-20241121011251065-418748176.png)


所以最近有很多反馈系统不支持AC\-3杜比音效的问题：


[win11 24h2 移除了ac\-3编解码支持（已找到解决方法) \- 电脑讨论(新) \- Chiphell \- 分享与交流用户体验](https://github.com)


[\[笔记本]如何在 Windows 11 24H2 之后安装杜比音频解码器 \|官方支持 \|华硕全球](https://github.com):[悠兔机场](https://xinnongbo.com)


[新版杜比（Dolby）的安装及设置\-联想知识库](https://github.com)


[在 Windows 11 版本 24H2 中恢复 Microsoft Dolby Digital 解码器/编码器 MFT 支持\-远景论坛\-微软极客社区](https://github.com)


大家可以从Store安装解码器扩展解决：[Dolby Digital Plus decoder for PC OEMs \- Windows官方下载 \| 微软应用商店 \| Microsoft Store](https://github.com)


默认不支持杜比音效，对OEM厂商是好事，只需要关注杜比认证，出了多少台安装杜比软件就缴纳多少版税。


 


参考资料：


 [“杜比音效”究竟是什么？ \- 知乎](https://github.com)[杜比Dolby Vision、 Dolby Atmos和 DolbyAudio是什么？有什么区别？ \- 知乎](https://github.com)[常见问题 \- Dolby Professional](https://github.com)[关于杜比全景声的一些概念，终于搞懂了！](https://github.com)


