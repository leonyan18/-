### int.gradle

放在user/用户下的.gradle文件夹下

### pip

直接把pip文件夹放到user/用户下

### idea proxy

http proxy里写 http://mirrors.aliyun.com

### maven

maven文件下conf/settingxml修改一下

### android

在build.gradle里的repositories里吧下面的语句写在第一位置

```xml
maven { url 'http://maven.aliyun.com/nexus/content/groups/public/' }
maven{ url 'http://maven.aliyun.com/nexus/content/repositories/jcenter'}
```

### host

没用再删掉

~~~
0.0.0.0 account.jetbrains.com
203.208.40.70 dl.google.com 
203.208.43.100 dl.l.google.com 
74.125.24.91 dl-ssl.google.com 
192.30.253.112 assets-cdn.github.com
151.101.88.249 github.global.ssl.fastly.net
~~~

### android 更新 

打开地址：http://ping.chinaz.com/，分别测试 dl.google.com 和 dl-ssl.google.com 的IP地址，将获取到的IP写入host文件里