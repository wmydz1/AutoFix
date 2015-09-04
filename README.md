# AutoFix
百分比布局 屏幕适配

```
dependencies {
 
    compile 'com.android.support:percent:22.2.0'
 
}

```

新的容器有了一些设置百分比的属性，下面我们来了解一下：
layout_widthPercent
设置控件宽度为父容器的宽的百分比


layout_heightPercent
设置控件高度为父容器的高的百分比


layout_marginPercent



layout_marginLeftPercent
设置控件与左边控件的距离为父容器的宽度的百分比


layout_marginTopPercent
设置控件与上方控件的距离为父容器的高度的百分比


layout_marginRightPercent
设置控件与右边控件的距离为父容器的宽度的百分比


layout_marginBottomPercent
设置控件与下方控件的距离为父容器的高度的百分比


layout_marginStartPercent
与上面的说明类似


layout_marginEndPercent
与上面的说明类似


从命名的方式我们可以知道，原来用某些具体单位（如dp）的设置现在都可以用百分比的方式进行设置了，例如设置控件的宽度layout_width原来我们是这样玩的android:layout_width="match_parent"现在用了百分比的属性之后呢，可以这样玩了app:layout_widthPercent="50%"，这里的百分比是相对于父容器而言的。


使用介绍：
官方文档地址：https://juliengenoud.github.io/android-percent-support-lib-sample/

在布局的xml文件需要添加下面这行来声明
[XML] 纯文本查看 复制代码
?
1
xmlns:app="http://schemas.android.com/apk/res-auto"


