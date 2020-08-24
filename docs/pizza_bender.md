by fish
1、发现一个get请求

GET /dujok/kevyl.php?l=ranec11.cab HTTP/1.1

Accept: */*

Accept-Language: en-US

Accept-Encoding: gzip, deflate

User-Agent: Mozilla/4.0 (compatible; MSIE 7.0; Windows NT 10.0; WOW64; Trident/7.0; .NET4.0C; .NET4.0E)

Host: ncznw6a.com

Connection: Keep-Alive

2、追踪http流，发现提示该程序不能运行在DOS模式下

![image-20200825002644688](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20200825002644688.png)

3、不清楚ranec11.cab，搜索一下，发现

| 日期                | 黑名单                   | 网址                                             |
| :------------------ | :----------------------- | :----------------------------------------------- |
| 2020-08-21 21:15:37 | 恶意软件下载（Abuse.ch） | http://ncznw6a.com/dujok/kevyl.php?l=ranec9.cab  |
| 2020-08-21 21:15:38 | 恶意软件下载（Abuse.ch） | http://ncznw6a.com/dujok/kevyl.php?l=ranec1.cab  |
| 2020-08-21 21:15:38 | 恶意软件下载（Abuse.ch） | http://ncznw6a.com/dujok/kevyl.php?l=ranec5.cab  |
| 2020-08-21 21:15:31 | 恶意软件下载（Abuse.ch） | http://ncznw6a.com/dujok/kevyl.php?l=ranec15.cab |
| 2020-08-21 21:15:31 | 恶意软件下载（Abuse.ch） | http://ncznw6a.com/dujok/kevyl.php?l=ranec14.cab |
| 2020-08-21 21:15:36 | 恶意软件下载（Abuse.ch） | http://ncznw6a.com/dujok/kevyl.php?l=ranec12.cab |
| 2020-08-21 21:15:38 | 恶意软件下载（Abuse.ch） | http://ncznw6a.com/dujok/kevyl.php?l=ranec2.cab  |
| 2020-08-21 21:15:31 | 恶意软件下载（Abuse.ch） | http://ncznw6a.com/dujok/kevyl.php?l=ranec13.cab |
| 2020-08-21 21:15:37 | 恶意软件下载（Abuse.ch） | http://ncznw6a.com/dujok/kevyl.php?l=ranec10.cab |
| 2020-08-21 21:15:37 | 恶意软件下载（Abuse.ch） | http://ncznw6a.com/dujok/kevyl.php?l=ranec11.cab |