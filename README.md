# notes
笔记记录
<h1>面试：</h1>
<hr/>
<h2>谷歌浏览器下，不支持css字体小于12px的解决方法？</h2>
<h4>使用transform:scale()</h4>
<h5>
<style>
	p{font-size:10px;-webkit-transform:scale(0.8);}
	/*这里的数字0.8，是缩放比例，可以根据情况变化。*/
</style>
	&lt;p&gt;字体大小兼容性测试&lt;/p&gt;
</h5>
<hr/>
<h2>HTML里面的行内元素，块级元素都知道，那么空元素有哪些呢？【常用】</h2>
<h3>行内：a\br\code\img\font\em\span\label\img\strong\input\b</h3>
<h3>块级：div\ul\li\ol\h1~h6\hr\p\tabel\fieldset</h3>
<h3>空元素：[没有关闭空间的元素]br\hr\html\xhtml\xml</h3>
<hr/>

<h1>标签：</h1>
<h2><a href="marquee.html">marquee 广告轮播</a></h2>
<h3>语法：&lt;marquee&gt;&lt;/marquee &gt;</h3>
<hr/>
<h3>属性：</h3>
<h4>behavior 设定滚动方式：</h4>
<h5>alternate:来回滚动；scorll重复滚动；slide:不重复滚动</h5>
<h4>direction 设定活动字幕的滚动方向</h4>
<h5>down、 left、 right 、 up</h5>
<h4>width、height</h4>
<h4>loop 设定滚动次数：</h4>
<h5>loop="-1" 无限【默认】；</h5>
<h4>scrollamount设定活动字幕的滚动速度，单位pixels</h4>
<h4>scrolldelay设定活动字幕滚动两次之间的延迟时间，单位millisecond（毫秒）</h4>
<hr/>
<h1>CSS3 属性</h1>
<hr/>
<h2>box-sizing：</h2>
<h3>语法：box-sizing ： content-box || border-box || inherit</h3>
<h4>块元素浏览器默认计算方式是：左右border+左右padding+左右margin+内容宽度width</h4>
<h4>box-sizing的取值为：content-box/padding-box/border-box</h4>
<h5>(1)content-box(w3c标准):这种计算方式要求将浏览器width属性应用到内容上，所以计算方式与浏览器一样 ，没必要设置</h5>
<h5>padding-box:这种计算方式中width属性=内容宽度+padding宽度*2 </h5>
<h5>border-box（传统IE浏览器）:将width属性应用到border区域（包含border大小），width=内容宽度+border宽度+padding宽度，border变化只影响内容宽度</h5>
<h3>如图：</h3>
<img src="img/box-sizing-img-box.png" height="499" width="499" alt="content-box与border-box 对比">