# -demo
用css3写的响应式布局项目。。。
这是整体框架结构
![image](https://github.com/Siyunlongshuai/-demo/blob/master/img/%E5%93%8D%E5%BA%94%E5%BC%8F%E5%B8%83%E5%B1%80%E6%80%BB%E5%9B%BE.png)
###其实也就分为三大步骤：
1：先用用html写出整体框架，
2：用css3再把样式补全，其中一些小问题自己挑。最重要的还是清除浮动的事，
   最好在开头定义一个样式。
    .clearfix::after{
        content: "";
        display: "";
        clear: "";
    }
    这只是清除浮动的一种，不过用的是最多的，还有好几种建议自己看一下：毕竟多了解的好嘛。。。。
 3.js部分自己写也可以。自己再去调试一下，就差不多了。
 ##js中那个轮播图用了GitHub上的轮播图插件，里面有介绍怎么使用的，按照他的要求就可以，可以大大减少
 开发的时间，最好是搞懂原理。这样会让你事半功倍的，无论什么都是一样的。
 引用图片的时候还要考虑到图形的适应，用了这个方法
 <picture>
    <source srcset = ".....png" media="(min-width:50em)"> </source>
    <source srcset = ".....png" media="(min-width:30em)"> </source>
    <img srcset="img/ad002.png" >
 </picture>
 可以在不同的屏幕引入不同的图片，让页面看着比较舒服。
 
