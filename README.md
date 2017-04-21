# ZhiFouWeather

知否天气是一款简洁、易用的天气App，遵循Material Design风格，只看天气。

一、主要实现功能：

·卡片展现：当前天气情况（包括天气图标、当前温度、最高温度、最低温度、PM2.5值、空气质量）

·卡片展现：当天未来几小时天气情况（包括时间显示、温度、湿度、风速）

·卡片展现：生活建议（包括穿衣指数、运动指数、旅游指数、感冒指数）

·卡片展现：未来一周天气情况（包括天气图标展示、日期、温度、天气情况、降水、风速）

·选择当前城市

·添加多个城市

·删除某个城市

·设置定时更新数据频率

·缓存数据，减少网络请求，保证离线查看

·内置两套图标（设置里更改）



二、权限说明：

 	 <!--用于进行网络定位-->
	<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
	<!--用于访问GPS定位-->
	<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>
	<!--获取运营商信息，用于支持提供运营商信息相关的接口-->
	<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE"/>
	<!--用于访问wifi网络信息，wifi信息会用于进行网络定位-->
	<uses-permission android:name="android.permission.ACCESS_WIFI_STATE"/>
	<!--这个权限用于获取wifi的获取权限，wifi信息会用来进行网络定位-->
	<uses-permission android:name="android.permission.CHANGE_WIFI_STATE"/>
	<!--用于访问网络，网络定位需要上网-->
	<uses-permission android:name="android.permission.INTERNET"/>
	<!--用于读取手机当前的状态-->
	<uses-permission android:name="android.permission.READ_PHONE_STATE"/>
	<!--写入扩展存储，向扩展卡写入数据，用于写入缓存定位数据-->
	<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
	<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
  
  
  
三、此版本特点：
  
  ·卡片UI（含有北京，上海，苏州）
  
  ·代码逻辑和规范
  
  ·关于页面沉浸式
  
  ·多城市订阅数量
  
  ·多城市管理
  
  ·首页UI更丰富
  
  ·反馈和意见
  
  ·美化的关于页面
  
  ·定位逻辑实现
  
  ·SP的统一化
  
  ·Error界面的设计
  
  ·通知栏常驻
  
  ·自动更新频率（0为不自动更新）
  
  
  
  
四、TODO：
  
  1.桌面小部件
  
  2.天气语音播报
  
  3.更好、更多的天气icon ———— 找到一个更好图标的网站，基于react-native开源技术：react-native icons 网址：https://oblador.github.io/react-native-vector-icons/
  
  4.自动定位
  
  5.自由定制的Item界面
  
  6.引导页面
  
  
  
五、公开API：

1.天气数据来源于： 和风天气

2.城市信息来源于： CSDN

3.地理定位服务： 高德地图



六、开源技术：

1.Rxjava.一个基于事件订阅的异步执行的一个类库。

2.RxAndroid.扩展库，更好的兼容了Android特性，比如主线程，UI事件等。

3.Retrofit.对okhttp做了一层封装。把网络请求都交给给了Okhttp，通过简单的配置就能使用retrofit来进行网络请求。

4.Glide.基于Android的轻量级缓存框架。



七、截图：

<<<<<<< HEAD

=======
![image](https://github.com/yangjing318/ZhiFouWeather/imagesFolder/Screenshot_1492346778.png)

![image](https://github.com/yangjing318/ZhiFouWeather/imagesFolder/Screenshot_1492346783.png)

![image](https://github.com/yangjing318/ZhiFouWeather/imagesFolder/Screenshot_1492346788.png)

![image](https://github.com/yangjing318/ZhiFouWeather/imagesFolder/Screenshot_1492346821.png)

![image](https://github.com/yangjing318/ZhiFouWeather/imagesFolder/Screenshot_1492346915.png)

![image](https://github.com/yangjing318/ZhiFouWeather/imagesFolder/Screenshot_1492347066.png)

![image](https://github.com/yangjing318/ZhiFouWeather/imagesFolder/Screenshot_1492347248.png)

![image](https://github.com/yangjing318/ZhiFouWeather/imagesFolder/Screenshot_1492347391.png)

>>>>>>> update README.md


