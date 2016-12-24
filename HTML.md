<h2>HTML常见标签</h2>
<p>html为网页标签，<!DOCTYPE html>表示这是一个HTML格式的文件</p>
> head为头部文件，包含引用的外部文件链接，网页标题，网页样式，脚本语言等元数据.

p标签表示一个段落，img标签表示一个图片，a表示一个链接。下面列举一些常用的标签。
* ul>li，无序列表标签
- ol>li，有序；列表标签
+ dl>dt，自定义列表
+ button，定义按钮
+ table，表格标签

<p>要查看更多标签，请到[W3CSchool](http://www.w3school.com.cn/)</p>
<h2>一个典型的HTML文件<h2>


![无标题.png](http://upload-images.jianshu.io/upload_images/4061504-c3af705f80c1f518.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
典型代码如下：
```
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
<div class="item">
	<h1 class="item">一级标题</h1>
<ul id="ik">
	<li class="cl">列表1</li>
	<li class="cl">列表2</li>
	<li class="cl">列表3</li>
	<li class="cl">列表4</li>
</ul>
</div>
<p class="test">这是一个段落</p>
<h2 class="hsajsb" id="gsxah"></h2>
</body>
</html>
```
