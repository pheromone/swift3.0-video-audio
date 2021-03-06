 # swift3.0-video-audio<br/>
 [ oc版本请点我 ]( https://github.com/pheromone/OC-video-audio)  <br/>
 另:[ JS与OC的交互篇 ]( http://www.cnblogs.com/shaoting/p/5247208.html)  <br/>
 本项目采用swift3.0所写,适配iOS9.0+,所有界面均采用代码布局. <br/>
 第一个tab写的是简单直播,传统MVC模式,第二个tab写的是简单网络音乐播放器.传说MVVM模式(怎么看怎么不对) ,第三个tab只是一些杂类    <br/>
 # 采用的第三方 <br/>
    pod 'SDWebImage',  ' ~> 3.8.2 ' 
    pod 'Alamofire',  ' ~> 4.2.0 ' 
    pod 'SnapKit',  ' ~> 3.1.2 ' 
    

 # 简单直播 <br/>
    直播框架采用 [ Bilibili的ijkplayer ]( https://github.com/Bilibili/ijkplayer)  <br/>
    感谢以下大神的帮助.<br/>
    想要学习更深层次的直播内容(如:搭建Web服务器,框架集成,原理,美颜,推流,采集,送礼物动画等可以学习大神们的博客)<br/>
  *  [ 袁峥Seemygo ]( http://www.jianshu.com/u/b09c3959ab3b)   <br/>
  *  [ OneTea ]( http://www.jianshu.com/u/fd4f9c1d72e2)    <br/>
  *  [ Swift 3 - 映客直播iOS版 ]( http://www.swiftv.cn/course/itdrunk0)   <br/>
  *  [ 小波说雨燕Github ]( https://github.com/yagamis)   <br/>
  
   
 - [x] MVC模式<br/>
 - [x] 播放<br/>
 - [x] 播放界面背景虚化<br/>
 - [x] 简单送礼物动画<br/>
 - [ ] 其他完善 <br/>
 
 #效果截图:<br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/video1.png) <br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/video2.gif) <br/>
 <br/>
 
 ----
# 简单网络音乐播放器 <br/>
   播放框架采用系统的AVPlayer
 - [x] MVVM模式<br/>
 - [x] 简单播放<br/>
 - [ ] 其他完善<br/>
 
  #效果截图:<br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/audio1.png) <br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/audio2.png) <br/>
 <br/>
# 杂类 <br/>
暂时转回原生一周,简单学习下,使用该tab记录下 <br/>
![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/tab3.png) <br/>

## 1.tableView联动 CollectionView联动 <br/>
感谢  *  [ leejayID ]( https://github.com/leejayID/Linkage-Swift)   <br/>  
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/tableView%E8%81%94%E5%8A%A8.gif) <br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/collectionVIew%E8%81%94%E5%8A%A8.gif) <br/>
## 2. 按钮 扩展 <br/>
感谢 找不到来源了  <br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/%E6%8C%89%E9%92%AE%E6%89%A9%E5%B1%95.png) <br/>
## 3.时间轴效果  <br/>
感谢    *  [ 航歌 ]( http://www.hangge.com/blog/cache/detail_1383.html)   <br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/%E6%97%B6%E9%97%B4%E8%BD%B4.png) <br/>
 ## 4.下拉放大 + 导航栏渐隐 <br/>
感谢    *  [ 下拉放大 + 导航栏渐隐 ]( http://blog.csdn.net/wj610671226/article/details/50498175)   <br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/%E4%B8%8B%E6%8B%89%E6%94%BE%E5%A4%A7%2B%E5%AF%BC%E8%88%AA%E6%A0%8F%E6%B8%90%E5%8F%98.gif) <br/>
 ## 5.分页控制器 <br/>
感谢    *  [ 分页控制器 ]( https://github.com/wubianxiaoxian/SKFPageView)   <br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/%E5%88%86%E9%A1%B5%E6%8E%A7%E5%88%B6%E5%99%A8.gif) <br/>
 ## 6.刮刮卡 <br/>
感谢    *  [ 航歌 ]( http://www.hangge.com/blog/cache/detail_1660.html)   <br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/%E5%88%AE%E5%88%AE%E5%8D%A1.png) 
## 7.检测人脸并打码 
感谢    *  [ 航歌 ]( http://www.hangge.com/blog/cache/detail_907.html)   <br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/%E6%A3%80%E6%B5%8B%E4%BA%BA%E8%84%B8%E5%B9%B6%E6%89%93%E7%A0%81.png) <br/>
 ## 8.广告页面渐隐效果 + 广告页面
感谢    *  [ 航歌 ]( http://www.hangge.com/blog/cache/detail_1246.html)   <br/>
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/%E5%B9%BF%E5%91%8A%E9%A1%B5%E9%9D%A2.png) 
 ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/%E5%B9%BF%E5%91%8A%E9%80%90%E6%B8%90%E9%9A%90%E8%97%8F.png) 
 <br/>
## 9.国际化 
感谢    *  [ VV木公子 ]( http://www.jianshu.com/p/88c1b65e3ddb)   <br/>
 <br/>
 ## 9.修改数字键盘
 感谢    *  [ 航歌 ]( http://www.hangge.com/blog/cache/detail_1419.html)   <br/>
  ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/%E6%95%B0%E5%AD%97%E9%94%AE%E7%9B%98.png) 
## 10.   iOS10.3后修改icon
 感谢    *  [ iOS 10.3 如何更换 app 图标 ]( http://www.jianshu.com/p/f6f328123923)   <br/>
  ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/%E4%BF%AE%E6%94%B9icon.png)
  ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/icon1.png)
  ![image](https://github.com/pheromone/swift-video-audio/blob/master/%E6%88%AA%E5%9B%BE/icon2.png)
  

 <br/>
 
