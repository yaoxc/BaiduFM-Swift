# BaiduFM-Swift
百度FM, swift语言实现，基于最新xcode6.3+swift1.2,初步只是为了实现功能，代码比较粗燥，后面有时间会整理。APP用的百度音乐API接口并非公共的，

##API接口申明
-本APP接口使用百度FM非公开API,音乐版权归百度所有

##功能

-可以下拉刷新歌曲列表

-歌词自动滚动

-实时显示歌曲播放进度

-暂停继续播放

-上一曲下一曲

-歌曲类型列表

-分类歌曲列表

-支持后台播放

-锁屏显示歌曲专辑信息

-锁屏控制音乐下一曲/上一曲、暂停播放


##项目截图
- 锁屏显示、播放控制![项目截图0](https://github.com/belm/BaiduFM-Swift/blob/master/BaiduFM-Swift_00.jpg?raw=true)

- 项目首页![项目截图1](https://github.com/belm/BaiduFM-Swift/blob/master/BaiduFM-Swift_01.jpg?raw=true)

- 歌曲分类![项目截图2](https://github.com/belm/BaiduFM-Swift/blob/master/BaiduFM-Swift_02.jpg?raw=true)

- 歌曲列表![项目截图3](https://github.com/belm/BaiduFM-Swift/blob/master/BaiduFM-Swift_03.jpg?raw=true)

##项目使用注意事项
-项目里使用COCOAPODS管理第三方库，运行前请执行pod install安装依赖库

##项目使用的第三方库

-[网络库Alamofire](https://github.com/Alamofire/Alamofire)

-[JSON解析SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON)

##使用的swift知识点
-网络请求

-JSON解析

-swift正则

-swift单例

-下拉刷新UIRefreshControl，歌曲进度UIProgressView，歌词滚动UITextView

-闭包

-get，set，didSet

-使用MPMoviePlayerController在线播放网络mp3 

##待完成功能
-下载歌曲到本地

-收藏喜欢的音乐

-背景播放支持(已经完成)

-播放音乐改用AVAudioPlayer

-第三方库合并(已经改用COCOAPODS管理)

##联系我
- [QQ邮箱](mailto:belm@vip.qq.com)

