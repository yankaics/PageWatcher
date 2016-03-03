# 网页监控助手(PageWatcher)
一款能够监控网页内容改变，并发出提醒的软件。可以用于抢课，抢票，秒杀等等。

>最近要选英语课了，但选课时间并未通知，为了能在选课系统开放的第一时间得知消息，写了一个能持续监听网站信息变动的程序，这次选择编写chrome的插件来实现这个功能。

##已实现功能：

1. 自定义刷新时间间隔，自动刷新网页，当网页内容发生改变时，进行提示
2. 提示分为3种方式，声音提示、桌面弹窗提示、发送QQ邮件提示

 ![popup截图](https://raw.githubusercontent.com/liyumeng/PageWatcher/resource/images/example1.png)

##TODO:

1. 设置提醒邮箱地址
2. 自定义每天的刷新时间段，例如在晚间不开启自动刷新
3. 自定义是否弹窗、是否播放音乐提醒、是否发送邮件提醒
