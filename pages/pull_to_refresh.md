# index
* [Android-PullToRefresh](#android-pulltorefresh)
* [android-Ultra-Pull-To-Refresh](#android-ultra-pull-to-refresh)
* [SwipeRefreshLayout](#swiperefreshlayout)
* [BGARefreshLayout-Android](#bgarefreshlayout-android)

[Pull to refresh框架的详细对比](https://github.com/desmond1121/Android-Ptr-Comparison)，这位同学非常的用心。

## [Android-PullToRefresh](https://github.com/chrisbanes/Android-PullToRefresh)
应该最早的一个下拉刷新框架，目前已经不维护。  
功能非常强大，支持ListView，ExpandableListView，GridView，WebView，ScrollView，HorizontalScrollView，ViewPager等。不过扩展性稍微弱一点。

## [android-Ultra-Pull-To-Refresh](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh)
![](https://camo.githubusercontent.com/588a2ef2cdcfb6c71e88437df486226dd15605b3/687474703a2f2f737261696e2d6769746875622e71696e6975646e2e636f6d2f756c7472612d7074722f73746f72652d686f7573652d737472696e672d61727261792e676966)

这个是对第一个替换和改良方案，定制性很强，可以嵌套任意View，推荐使用该框架。  
加载更多的功能，需要自己去实现。    
> 对比  [Android-PullToRefresh](https://github.com/chrisbanes/Android-PullToRefresh) 项目，UltraPTR 没有实现 加载更多 的功能，但我认为 下拉刷新 和 加载更多 不是同一层次的功能， 下拉刷新 有更广泛的需求，可以适用于任何页面。而 加载更多 的功能应该交由具体的 Content 自己去实现。这应该是和 Google 官方推出 SwipeRefreshLayout 是相同的设计思路，但对比 SwipeRefreshLayout， UltraPTR 更灵活，更容易拓展。

源码分析：[android-Ultra-Pull-to-Refresh](http://a.codekk.com/detail/Android/Grumoon/android-Ultra-Pull-To-Refresh%20%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90)

## [SwipeRefreshLayout](http://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html)
官方出品，在support-v4包中，扩展性上比较弱。

## [BGARefreshLayout-Android](https://github.com/bingoogolapple/BGARefreshLayout-Android)
![](https://camo.githubusercontent.com/912ee9a45b5ed7063bd6fe7634f8130953a7051d/687474703a2f2f37786b39646a2e636f6d312e7a302e676c622e636c6f7564646e2e636f6d2f726566726573686c61796f75742f73637265656e73686f74732f6267615f726566726573686c61796f7574312e676966)

多种下拉刷新效果、上拉加载更多、可配置自定义头部广告位.
功能看起来挺多的，可以实现多种下拉刷新效果。
