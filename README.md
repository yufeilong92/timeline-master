# H-Express Library--------timeline

![Platform](https://img.shields.io/badge/platform-Android-blue.svg)![Release](https://img.shields.io/badge/debug-1.0.0-orange.svg)![Gradle](https://img.shields.io/badge/gradle-2.0.0-blue.svg)[ ![Download](https://api.bintray.com/packages/qht1003077897/maven/timeline/images/download.svg) ](https://bintray.com/qht1003077897/maven/timeline/_latestVersion)

A view that mimics the timeline，you can download it when you need logistics tracking or time to record。

这是母项目 H-Express 中的那个自定义时间轴view，现抽取出来分享给大家。

[timeline  APK](https://github.com/qht1003077897/timeline/blob/master/apk/app-debug.apk)
----------
## Screenshots

![这里写图片描述](http://img.blog.csdn.net/20170801094254090?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMjUzNDgzMQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![这里写图片描述](http://img.blog.csdn.net/20170801094302201?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMjUzNDgzMQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

左边为H-Express中的效果，右边为原始效果，横向和竖向。

----------
## Import

AS: 
```
	dependencies {
	        compile 'com.qht1003077897.timeline:timelinelibrary:0.1'
	}

```
EC: 
使用eclipse的同学直接到项目的github地址下面timelinelibrary中拷贝出两个类，一个attrs出来，放到自己项目中即可。

----------
## Clone

```
	 clone https://github.com/qht1003077897/timeline.git
```

----------
## Attributes


| name | format | description |
| -----|:----:| ----:|
| markerSize | dimension | 中心圆大小，单位dp   |
| marker    | color/reference    |  圆点颜色或者图片   |
| beginLine    | color/reference    |  上面(左边)线段颜色或者图片   |
| endLine    | color/reference    |   下面(右边)线段颜色或者图片  |
| lineSize    | dimension    |   线段粗细，单位dp  |
| oritation    | boolean    |   时间轴的方向，ture横向，false竖向  |

<br>

----------
## Usage
 
```
 	<com.bt.mylibrary.TimeLineMarkerView
        android:id="@+id/time1"
        android:layout_width="150dp"
        android:layout_height="100dp"
        android:paddingTop="20dp"
        app:beginLine="@color/blue_sky"
        app:endLine="@color/blue_sky"
        app:oritation="true"
        app:marker="@drawable/timeline_bg_blue"/>
```
----------
## About me

An android developer in XI'AN.

QQ: [1003077897]()
csdn：http://blog.csdn.net/u012534831

## License
-------

     MIT License
     
    Copyright (c) 2016-2018  qht1003077897

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.


---
 
 

