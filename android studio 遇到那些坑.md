# android studio 遇到那些坑

---
## 坑一

>  Warning:Gradle version 2.10 is required. Current version is 2.8. If using the gradle wrapper, try editing the distributionUrl in F:\work\qxueyou\gradle\wrapper\gradle-wrapper.properties to gradle-2.10-all.zip

![](image/bug2.jpg)

**解决办法:**

![](image/bug3.png)

* 参考链接:[Android开发出现Warning:Gradle version 2.10 is required. Current version is 2.8. If u](http://www.ithao123.cn/content-10783272.html)

## 坑二

> nothing to show device
解决方法一
![](image/bug1.png)
解决方法二:删除下面的文件即可
![](image/bug7.jpg)

**解决办法:**

![](image/bug4.jpg)

* 参考链接: [Android: no running Device](http://stackoverflow.com/questions/5924592/android-no-running-device)

## android studio 出现问题

- 把此文件架下东西都删除

## 比较靠谱的方法:是(亲测有效)

 > ** 先把adb进程在任务管理器中结束掉,关掉所有模拟器,clean 一下,先点击运行,出现提示后,再点击启动Genmotion**

![](image/bug5.jpg)

- 更新android studio 

![](image/bug6.jpg)

## android studio 导入eclipse项目乱码问题

**参见:**

 http://jingyan.baidu.com/article/d8072ac463b206ec95cefdd5.html
 http://jingyan.baidu.com/article/f0e83a2585afcd22e59101ff.html


## Error running app: Instant Run requires 'Tools | Android | Enable ADB integration' to be enabled.

> 菜单栏，Tools -> Adnroid -> enable ADB integration，再次感谢桃花林里练醉拳。






