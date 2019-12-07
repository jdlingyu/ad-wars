## 悟空净化

经常使用微博、华尔街见闻、哈罗单车等应用，每次打开都有广告，而且广告天天还重复，低俗：数码宝贝、真人竞技、澳门首家在线赌场。

每次打开应用也许只是扫个二维码、看个行情，却需要等待好几秒，为了解决这个问题，可谓不遗余力：

1. 八戒助手(前身广告住手)：通过辅助服务来点击的，有些应用很顽固支持不好，可以尝试点击屏幕坐标完成；
2. 悟空加速：由于八戒助手依赖辅助服务的局限性，以消灭启动页广告的目标，基于 Xposed 开发了悟空加速。在跳过效果上几乎完美：比如迅雷/知乎；
3. 唐僧藏经：由于每个应用的跳过规则都不同，方便大家跳过规则的分享，开发了规则数据共享：可以导出/发布广告规则。

为了降低使用门槛，新完成悟空净化：集合八戒/悟空/唐僧功能，自动同步云端规则，更多姿势去除广告...
### 八戒
1. 八戒助手
> 借助无障碍服务，跳过启动页广告
2. 八戒任务
> 多个页面的点击组合成八戒任务

<img src="https://raw.githubusercontent.com/wiki/jdlingyu/ad-wars/images/bajie.png" width="250">

### 悟空
1. 悟空加速
> 基于 Xposed，跳过启动页的广告
2. Url 拦截
> 基于 Xposed，拦截广告 Url
3. 广告文件替换
> 通过用同名的空文件夹替换广告，达到去除广告
4. Hosts 管理
> 通过替换 hosts，应用无法下载广告

<img src="https://raw.githubusercontent.com/wiki/jdlingyu/ad-wars/images/wukong.png" width="250">

### 社区
> 基于社区，大家交流和共享解码
<img src="https://raw.githubusercontent.com/wiki/jdlingyu/ad-wars/images/bbs.png" width="250">

### `更多指南`
> [大圣净化 使用帮助](https://github.com/jdlingyu/ad-wars/wiki)

### 应用下载地址(需要激活码)
> [大圣净化 https://fir.im/adwars](https://fir.im/adwars)
1. 永久有效，可循环激活 
2. 可在线购买激活码 