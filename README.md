# css library
css I want collate data about css.
Today let me start it.
### 一、Compatible with IE6 (对IE6等比版本兼容的css样式)
[csshack.css](https://github.com/happyzhanhan/csslibrary/blob/master/Compatible/csshack.css)(css hack)
当你需要兼容IE6.7.8等低配的时候可以愉快的使用这个小技巧

#### 仅IE6识别 _
```
_background-color:#1e0bd1;
```
#### 仅IE7识别 * +
```
* +html .bb{background-color:#a200ff;}
```
#### 仅火狐识别 @-moz-document url-prefix(){}
```
@-moz-document url-prefix(){.bb{background-color:#00ff00;}}
```
#### IE6,7识别 +
```
+background-color:#a200ff;
```
#### IE6,7,8识别 \9
```
.background-color:#00deff\9;
```



### 二、Css reset （css样式重置）

[reset.css](https://github.com/happyzhanhan/csslibrary/tree/master/resetcss)(重置样式表)
这个几乎是开始新项目必备哦

### 三、Css animate （css动态样式库）
[animate.css](https://github.com/happyzhanhan/csslibrary/tree/master/animatecss)(动态样式表)
这个是为了让页面更好的使用动画效果，而且很多js合作使用

[官方animate.css可以看一下](https://daneden.github.io/animate.css/)(主要参照效果和使用方法)

|Class Name||||	
|:--:|:--:|:--:|:--:|		
|bounce|	flash|	pulse|	rubberBand|
|shake|	headShake|	swing|	tada|
|wobble|	jello|	bounceIn|	bounceInDown|
|bounceInLeft|	bounceInRight|	bounceInUp|	bounceOut|
|bounceOutDown|	bounceOutLeft|	bounceOutRight|	bounceOutUp|
|fadeIn|	fadeInDown|	fadeInDownBig|	fadeInLeft|
|fadeInLeftBig	|fadeInRight|	fadeInRightBig|	fadeInUp|
|fadeInUpBig|	fadeOut	|fadeOutDown	|fadeOutDownBig|
|fadeOutLeft|	fadeOutLeftBig|	fadeOutRight	|fadeOutRightBig|
|fadeOutUp|	fadeOutUpBig	|flipInX	|flipInY|
|flipOutX|	flipOutY	|lightSpeedIn|	lightSpeedOut|
|rotateIn|	rotateInDownLeft|	rotateInDownRight|	rotateInUpLeft|
|rotateInUpRight|	rotateOut|	rotateOutDownLeft|	rotateOutDownRight|
|rotateOutUpLeft|	rotateOutUpRight|	hinge|	jackInTheBox|
|rollIn|	rollOut	|zoomIn|	zoomInDown|
|zoomInLeft|	zoomInRight|	zoomInUp|	zoomOut|
|zoomOutDown|	zoomOutLeft	|zoomOutRight|	zoomOutUp|
|slideInDown|	slideInLeft	|slideInRight	|slideInUp|
|slideOutDown	|slideOutLeft|	slideOutRight|	slideOutUp|



使用方法：
#### 1.下载引入样式表：
```
<link rel="stylesheet" href="animate.css">
```

#### 2.行间使用样式：
```
<h1 class="animated infinite bounce">Example</h1>
```



### 四、The processor of css  （css的处理器）



### 五、New style I know once I see （新的css好用的样式每次见到记录学习）
