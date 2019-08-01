# HTML5 CSS3



## 1.      CSS3有哪些新特性？

CSS3实现圆角（border-radius），阴影（box-shadow），

对文字加特效（text-shadow、），线性渐变（gradient），旋转（transform）

3.transform:rotate(9deg) scale(0.85,0.90) translate(0px,-30px) skew(-9deg,0deg);// 旋转,缩放,定位,倾斜

增加了更多的CSS选择器  多背景 rgba 

在CSS3中唯一引入的伪元素是 ::selection.

媒体查询，多栏布局

border-image

## 2.  html5有哪些新特性、移除了那些元素？如何处理HTML5新标签的浏览器兼容问题？如何区分 HTML 和 HTML5？

新特性：

1. 拖拽释放(Drag and drop) API 

2. 语义化更好的内容标签（header,nav,footer,aside,article,section）

3. 音频、视频API(audio,video)

4. 画布(Canvas) API
5. 地理(Geolocation) API

6. 本地离线存储 localStorage 长期存储数据，浏览器关闭后数据不丢失；

7. sessionStorage 的数据在浏览器关闭后自动删除

8. 表单控件，calendar、date、time、email、url、search  

9. 新的技术webworker, websocket, Geolocation

移除的元素：

1. 纯表现的元素：basefont，big，center，font, s，strike，tt，u；

2. 对可用性产生负面影响的元素：frame，frameset，noframes；

支持HTML5新标签：

```html
IE8/IE7/IE6支持通过 document.createElement 方法产生的标签，可以利用这一特性让这些浏览器支持 HTML5 新标签，浏览器支持新标签后，还需要添加标签默认的样式（当然最好的方式是直接使用成熟的框架、使用最多的是html5shim框架）：

<!--[if lt IE 9]>

<script>
src="http://html5shim.googlecode.com/svn/trunk/html5.js"</script>

<![endif]-->

如何区分： 

DOCTYPE声明新增的结构元素、功能元素
```



## 3.      本地存储（Local Storage ）和cookies（储存在用户本地终端上的数据）之间的区别是什么？

Cookies:服务器和客户端都可以访问；大小只有4KB左右；有有效期，过期后将会删除；

本地存储：只有本地浏览器端可访问数据，服务器不能访问本地存储直到故意通过POST或者GET的通道发送到服务器；每个域5MB；没有过期数据，它将保留知道用户从浏览器清除或者使用Javascript代码移除

## 4.      如何实现浏览器内多个标签页之间的通信?

调用 localstorge、cookies 等本地存储方式

## 5.      你如何对网站的文件和资源进行优化？

文件合并

文件最小化/文件压缩

使用CDN托管

缓存的使用

## 6.      什么是响应式设计？

它是关于网页制作的过程中让不同的设备有不同的尺寸和不同的功能。响应式设计是让所有的人能在这些设备上让网站运行正常 

## 7.      新的 HTML5 文档类型和字符集是？

答：HTML5文档类型：<!doctype html>

    HTML5使用的编码<meta charset="UTF-8">

## 8.      HTML5 Canvas 元素有什么用？

答：Canvas 元素用于在网页上绘制图形，该元素标签强大之处在于可以直接在 HTML 上进行图形操作。

## 9.      HTML5 存储类型有什么区别？

答：Media API、Text Track API、Application Cache API、User Interaction、Data Transfer API、Command API、Constraint Validation API、History API

## 10.   用H5+CSS3解决下导航栏最后一项掉下来的问题

## 11.   CSS3新增伪类有那些？

```html
p:first-of-type 选择属于其父元素的首个 <p> 元素的每个 <p> 元素。

p:last-of-type  选择属于其父元素的最后 <p> 元素的每个 <p> 元素。

p:only-of-type  选择属于其父元素唯一的 <p> 元素的每个 <p> 元素。

p:only-child    选择属于其父元素的唯一子元素的每个 <p> 元素。

p:nth-child(2)  选择属于其父元素的第二个子元素的每个 <p> 元素。

:enabled、:disabled 控制表单控件的禁用状态。
```

:checked，单选框或复选框被选中。

## 12.   请用CSS实现：一个矩形内容，有投影，有圆角，hover状态慢慢变透明。

css属性的熟练程度和实践经验

## 13.   描述下CSS3里实现元素动画的方法

动画相关属性的熟悉程度

## 14.   html5## CSS3有哪些新特性、移除了那些元素？如何处理HTML5新标签的浏览器兼容问题？如何区分 HTML 和 HTML5？

HTML5 现在已经不是 SGML 的子集，主要是关于图像，位置，存储，地理定位等功能的增加。

## * 绘画 canvas 元素

  用于媒介回放的 video 和 audio 元素

  本地离线存储 localStorage 长期存储数据，浏览器关闭后数据不丢失；

  sessionStorage 的数据在浏览器关闭后自动删除

  语意化更好的内容元素，比如 article、footer、header、nav、section

  表单控件，calendar、date、time、email、url、search

  CSS3实现圆角，阴影，对文字加特效，增加了更多的CSS选择器  多背景 rgba

  新的技术webworker, websockt, Geolocation

移除的元素

纯表现的元素：basefont，big，center，font, s，strike，tt，u；

对可用性产生负面影响的元素：frame，frameset，noframes；

## * 是IE8/IE7/IE6支持通过document.createElement方法产生的标签，

  可以利用这一特性让这些浏览器支持HTML5新标签，

  浏览器支持新标签后，还需要添加标签默认的样式：

## * 当然最好的方式是直接使用成熟的框架、使用最多的是html5shim框架

<!--[if lt IE 9]>

<script>
src="http://html5shim.googlecode.com/svn/trunk/html5.js"</script>

<![endif]-->

## 15.   你怎么来实现页面设计图，你认为前端应该如何高质量完成工作? 一个满屏 品 字布局 如何设计?

## * 首先划分成头部、body、脚部；。。。。。 

## * 实现效果图是最基本的工作，精确到2px；

  与设计师，产品经理的沟通和项目的参与

  做好的页面结构，页面重构和用户体验

  处理hack，兼容、写出优美的代码格式

  针对服务器的优化、拥抱 HTML5。

## 16.   你能描述一下渐进增强和优雅降级之间的不同吗?

渐进增强 progressive enhancement：针对低版本浏览器进行构建页面，保证最基本的功能，然后再针对高级浏览器进行效果、交互等改进和追加功能达到更好的用户体验。

优雅降级 graceful degradation：一开始就构建完整的功能，然后再针对低版本浏览器进行兼容。

　　区别：优雅降级是从复杂的现状开始，并试图减少用户体验的供给，而渐进增强则是从一个非常基础的，能够起作用的版本开始，并不断扩充，以适应未来环境的需要。降级（功能衰减）意味着往回看；而渐进增强则意味着朝前看，同时保证其根基处于安全地带。　

　　“优雅降级”观点

　　“优雅降级”观点认为应该针对那些最高级、最完善的浏览器来设计网站。而将那些被认为“过时”或有功能缺失的浏览器下的测试工作安排在开发周期的最后阶段，并把测试对象限定为主流浏览器（如 IE、Mozilla 等）的前一个版本。

　　在这种设计范例下，旧版的浏览器被认为仅能提供“简陋却无妨 (poor, but passable)” 的浏览体验。你可以做一些小的调整来适应某个特定的浏览器。但由于它们并非我们所关注的焦点，因此除了修复较大的错误之外，其它的差异将被直接忽略。

　　“渐进增强”观点

　　“渐进增强”观点则认为应关注于内容本身。

　　内容是我们建立网站的诱因。有的网站展示它，有的则收集它，有的寻求，有的操作，还有的网站甚至会包含以上的种种，但相同点是它们全都涉及到内容。这使得“渐进增强”成为一种更为合理的设计范例。这也是它立即被 Yahoo! 所采纳并用以构建其“分级式浏览器支持 (Graded Browser Support)”策略的原因所在。

 

　　**那么问题了。现在产品经理看到IE6,7,8网页效果相对高版本现代浏览器少了很多圆角，阴影（CSS3），要求兼容（使用图片背景，放弃CSS3），你会如何说服他？**

## 17.   为什么利用多个域名来存储网站资源会更有效？

CDN缓存更方便 

突破浏览器并发限制 

节约cookie带宽 

节约主域名的连接数，优化页面响应速度 

防止不必要的安全问题

## 18.   请谈一下你对网页标准和标准制定机构重要性的理解。

　　（无标准答案）网页标准和标准制定机构都是为了能让web发展的更‘健康’，开发者遵循统一的标准，降低开发难度，开发成本，SEO也会更好做，也不会因为滥用代码导致各种BUG、安全问题，最终提高网站易用性。

 

## 19.   请描述一下cookies，sessionStorage和localStorage的区别？　　

　　sessionStorage用于本地存储一个会话（session）中的数据，这些数据只有在同一个会话中的页面才能访问并且当会话结束后数据也随之销毁。因此sessionStorage不是一种持久化的本地存储，仅仅是会话级别的存储。而localStorage用于持久化的本地存储，除非主动删除数据，否则数据是永远不会过期的。

**web storage****和****cookie****的区别**

Web Storage的概念和cookie相似，区别是它是为了更大容量存储设计的。Cookie的大小是受限的，并且每次你请求一个新的页面的时候Cookie都会被发送过去，这样无形中浪费了带宽，另外cookie还需要指定作用域，不可以跨域调用。

除此之外，Web Storage拥有setItem,getItem,removeItem,clear等方法，不像cookie需要前端开发者自己封装setCookie，getCookie。但是Cookie也是不可以或缺的：Cookie的作用是与服务器进行交互，作为HTTP规范的一部分而存在 ，而Web Storage仅仅是为了在本地“存储”数据而生。

## 20.   知道css有个content属性吗？有什么作用？有什么应用？

知道。css的content属性专门应用在 before/after 伪元素上，用来插入生成内容。最常见的应用是利用伪类清除浮动。

//一种常见利用伪类清除浮动的代码

.clearfix:after {

    content:"."; //这里利用到了content属性
    
    display:block; 
    
    height:0;
    
    visibility:hidden; 
    
    clear:both; }

.clearfix { 

    *zoom:1; 

}

after伪元素通过 content 在元素的后面生成了内容为一个点的块级素，再利用clear:both清除浮动。

　　那么问题继续还有，**知道css计数器（序列数字字符自动递增）吗？如何通过css content属性实现css计数器？**

答案：css计数器是通过设置counter-reset 、counter-increment 两个属性 、及 counter()/counters()一个方法配合after / before 伪类实现。 

## 21.   如何在 HTML5 页面中嵌入音频?

HTML 5 包含嵌入音频文件的标准方式，支持的格式包括 MP3、Wav 和 Ogg：

<audio controls> 

  <source src="jamshed.mp3" type="audio/mpeg"> 

   Your browser does'nt support audio embedding feature. 

</audio>

## 22.   如何在 HTML5 页面中嵌入视频？

和音频一样，HTML5 定义了嵌入视频的标准方法，支持的格式包括：MP4、WebM 和 Ogg：

<video width="450" height="340" controls> 

  <source src="jamshed.mp4" type="video/mp4"> 

   Your browser does'nt support video embedding feature. 

</video> 

## 23.   HTML5 引入什么新的表单属性？

Datalist   datetime   output   keygen  date  month  week  time  number   range   emailurl

## 24.   CSS3新增伪类有那些？

 p:first-of-type 选择属于其父元素的首个 <p> 元素的每个 <p> 元素。

    p:last-of-type  选择属于其父元素的最后 <p> 元素的每个 <p> 元素。
    
    p:only-of-type  选择属于其父元素唯一的 <p> 元素的每个 <p> 元素。
    
    p:only-child    选择属于其父元素的唯一子元素的每个 <p> 元素。
    
    p:nth-child(2)  选择属于其父元素的第二个子元素的每个 <p> 元素。
    
    :enabled、:disabled 控制表单控件的禁用状态。

:checked，单选框或复选框被选中。

## 25.   (写)描述一段语义的html代码吧。

（HTML5中新增加的很多标签（如：<article>、<nav>、<header>和<footer>等）

就是基于语义化设计原则）  

< div id="header">

< h1>标题< /h1>

< h2>专注Web前端技术< /h2>

< /div>

语义 HTML 具有以下特性：

 

文字包裹在元素中，用以反映内容。例如：

段落包含在 <p> 元素中。

顺序表包含在<ol>元素中。

从其他来源引用的大型文字块包含在<blockquote>元素中。

HTML 元素不能用作语义用途以外的其他目的。例如：

<h1>包含标题，但并非用于放大文本。

<blockquote>包含大段引述，但并非用于文本缩进。

空白段落元素 ( <p></p> ) 并非用于跳行。

文本并不直接包含任何样式信息。例如：

不使用 <font> 或 <center> 等格式标记。

类或 ID 中不引用颜色或位置。

## 26.   cookie在浏览器和服务器间来回传递。 sessionStorage和localStorage区别

sessionStorage和localStorage的存储空间更大；

sessionStorage和localStorage有更多丰富易用的接口；

sessionStorage和localStorage各自独立的存储空间；

## 27.   html5有哪些新特性、移除了那些元素？如何处理HTML5新标签的浏览器兼容问题？如何区分 HTML 和 HTML5？

## * HTML5 现在已经不是 SGML 的子集，主要是关于图像，位置，存储，多任务等功能的增加。

## * 绘画 canvas  

  用于媒介回放的 video 和 audio 元素 

  本地离线存储 localStorage 长期存储数据，浏览器关闭后数据不丢失；

  sessionStorage 的数据在浏览器关闭后自动删除

  语意化更好的内容元素，比如 article、footer、header、nav、section 

  表单控件，calendar、date、time、email、url、search  

  新的技术webworker, websockt, Geolocation

## * 移除的元素

纯表现的元素：basefont，big，center，font, s，strike，tt，u；

对可用性产生负面影响的元素：frame，frameset，noframes；

支持HTML5新标签：

## * IE8/IE7/IE6支持通过document.createElement方法产生的标签，

  可以利用这一特性让这些浏览器支持HTML5新标签，

  浏览器支持新标签后，还需要添加标签默认的样式：

## * 当然最好的方式是直接使用成熟的框架、使用最多的是html5shim框架

<!--[if lt IE 9]>

<script> src="http://html5shim.googlecode.com/svn/trunk/html5.js"</script>
<![endif]-->

## 28.   如何区分： DOCTYPE声明## 新增的结构元素## 功能元素

## 29.   语义化的理解？

用正确的标签做正确的事情！

html语义化就是让页面的内容结构化，便于对浏览器、搜索引擎解析；

在没有样式CCS情况下也以一种文档格式显示，并且是容易阅读的。

搜索引擎的爬虫依赖于标记来确定上下文和各个关键字的权重，利于 SEO。

使阅读源代码的人对网站更容易将网站分块，便于阅读维护理解。

## 30.   HTML5的离线储存？

localStorage    长期存储数据，浏览器关闭后数据不丢失；

sessionStorage  数据在浏览器关闭后自动删除。

## 31.   写出HTML5的文档声明方式

|      | <DOCYPE html> |
| ---- | ------------- |
|      |               |

## 32.   HTML5和CSS3的新标签     

|      | HTML5： nav, footer, header, section, hgroup, video, time, canvas, audio...   CSS3: RGBA, opacity, text-shadow, box-shadow, border-radius, border-image,    border-color, transform...; |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 33.   自己对标签语义化的理解

    在我看来，语义化就是比如说一个段落， 那么我们就应该用 <p>标签来修饰，标题就应该用 <h?>标签等。符合文档语义的标签。

# 四、移动web开发

## 1、移动端常用类库及优缺点

知识面宽度，多多益善

## 2、Zepto库和JQ区别

Zepto相对jQuery更加轻量，主要用在移动端，jQuery也有对应的jQuerymobile移动端框架

# 五、Ajax

## 1、Ajax 是什么? 如何创建一个Ajax？

Ajax并不算是一种新的技术，全称是asychronous javascript and xml，可以说是已有技术的组合，主要用来实现客户端与服务器端的异步通信效果，实现页面的局部刷新，早期的浏览器并不能原生支持ajax，可以使用隐藏帧（iframe）方式变相实现异步效果，后来的浏览器提供了对ajax的原生支持

使用ajax原生方式发送请求主要通过XMLHttpRequest(标准浏览器)、ActiveXObject(IE浏览器)对象实现异步通信效果

基本步骤：

var xhr =null;//创建对象 

if(window.XMLHttpRequest){

   xhr = new XMLHttpRequest();

}else{

   xhr = new ActiveXObject("Microsoft.XMLHTTP");

}

     xhr.open(“方式”,”地址”,”标志位”);//初始化请求 
    
     xhr.setRequestHeader(“”,””);//设置http头信息 
    
     xhr.onreadystatechange =function(){}//指定回调函数 
    
     xhr.send();//发送请求 

js框架（jQuery/EXTJS等）提供的ajax  API对原生的ajax进行了封装，熟悉了基础理论，再学习别的框架就会得心应手，好多都是换汤不换药的内容 

## 2、同步和异步的区别?

同步：阻塞的

-张三叫李四去吃饭，李四一直忙得不停，张三一直等着，直到李四忙完两个人一块去吃饭

=浏览器向服务器请求数据，服务器比较忙，浏览器一直等着（页面白屏），直到服务器返回数据，浏览器才能显示页面

异步：非阻塞的

-张三叫李四去吃饭，李四在忙，张三说了一声然后自己就去吃饭了，李四忙完后自己去吃

=浏览器向服务器请求数据，服务器比较忙，浏览器可以自如的干原来的事情（显示页面），服务器返回数据的时候通知浏览器一声，浏览器把返回的数据再渲染到页面，局部更新

## 3、如何解决跨域问题?

理解跨域的概念：协议、域名、端口都相同才同域，否则都是跨域

出于安全考虑，服务器不允许ajax跨域获取数据，但是可以跨域获取文件内容，所以基于这一点，可以动态创建script标签，使用标签的src属性访问js文件的形式获取js脚本，并且这个js脚本中的内容是**函数调用**，该函数调用的参数是服务器返回的数据，为了获取这里的参数数据，需要事先在页面中定义回调函数，在回调函数中处理服务器返回的数据，这就是解决跨域问题的主流解决方案

## 4、页面编码和被请求的资源编码如果不一致如何处理？

对于ajax请求传递的参数，如果是get请求方式，参数如果传递中文，在有些浏览器会乱码，不同的浏览器对参数编码的处理方式不同，所以对于get请求的参数需要使用 encodeURIComponent函数对参数进行编码处理，后台开发语言都有相应的解码api。对于post请求不需要进行编码

## 5、简述ajax 的过程。

## 1. 创建XMLHttpRequest对象,也就是创建一个异步调用对象

## 2. 创建一个新的HTTP请求,并指定该HTTP请求的方法、URL及验证信息

## 3. 设置响应HTTP请求状态变化的函数

## 4. 发送HTTP请求

## 5. 获取异步调用返回的数据

## 6. 使用JavaScript和DOM实现局部刷新

## 6、阐述一下异步加载。

## 1. 异步加载的方案： 动态插入 script 标签

## 2. 通过 ajax 去获取 js 代码，然后通过 eval 执行

## 3. script 标签上添加 defer 或者 async 属性

## 4. 创建并插入 iframe，让它异步执行 js

## 7、请解释一下 JavaScript 的同源策略。

同源策略是客户端脚本（尤其是Javascript）的重要的安全度量标准。它最早出自Netscape Navigator2.0，其目的是防止某个文档或脚本从多个不同源装载。所谓同源指的是：协议，域名，端口相同，同源策略是一种安全协议，指一段脚本只能读取来自同一来源的窗口和文档的属性。

## 8、GET和POST的区别，何时使用POST？

GET：一般用于信息获取，使用URL传递参数，对所发送信息的数量也有限制，一般在2000个字符，有的浏览器是8000个字符

POST：一般用于修改服务器上的资源，对所发送的信息没有限制

在以下情况中，请使用 POST 请求：

## 1. 无法使用缓存文件（更新服务器上的文件或数据库）

## 2. 向服务器发送大量数据（POST 没有数据量限制）

## 3. 发送包含未知字符的用户输入时，POST 比 GET 更稳定也更可靠

## 9、ajax 是什么?ajax 的交互模型?同步和异步的区别?如何解决跨域问题?

 ## 1. 通过异步模式，提升了用户体验

 ## 2. 优化了浏览器和服务器之间的传输，减少不必要的数据往返，减少了带宽占用

## 3.  Ajax在客户端运行，承担了一部分本来由服务器承担的工作，减少了大用户量下的服务器负载。

## 10、 Ajax的最大的特点是什么。

    Ajax可以实现异步通信效果，实现页面局部刷新，带来更好的用户体验；按需获取数据，节约带宽资源； 

## 11、ajax的缺点

 1、ajax不支持浏览器back按钮。

 2、安全问题 AJAX暴露了与服务器交互的细节。

 3、对搜索引擎的支持比较弱。

 4、破坏了程序的异常机制。

## 12、ajax请求的时候get 和post方式的区别

get一般用来进行查询操作，url地址有长度限制，请求的参数都暴露在url地址当中，如果传递中文参数，需要自己进行编码操作，安全性较低。

post请求方式主要用来提交数据，没有数据长度的限制，提交的数据内容存在于http请求体中，数据不会暴漏在url地址中。

## 13、解释jsonp的原理，以及为什么不是真正的ajax

　　Jsonp并不是一种数据格式，而json是一种数据格式，jsonp是用来解决跨域获取数据的一种解决方案，具体是通过动态创建script标签，然后通过标签的src属性获取js文件中的js脚本，该脚本的内容是一个函数调用，参数就是服务器返回的数据，为了处理这些返回的数据，需要事先在页面定义好回调函数，本质上使用的并不是ajax技术

## 14、什么是Ajax和JSON，它们的优缺点。

Ajax是全称是asynchronous JavaScript andXML，即异步JavaScript和xml，用于在Web页面中实现异步数据交互，实现页面局部刷新。

优点：可以使得页面不重载全部内容的情况下加载局部内容，降低数据传输量，避免用户不断刷新或者跳转页面，提高用户体验

缺点：对搜索引擎不友好；要实现ajax下的前后退功能成本较大；可能造成请求数的增加跨域问题限制；

JSON是一种轻量级的数据交换格式，ECMA的一个子集

优点：轻量级、易于人的阅读和编写，便于机器（JavaScript）解析，支持复合数据类型（数组、对象、字符串、数字）

## 15、http常见的状态码有那些？分别代表是什么意思？

200 - 请求成功

301 - 资源（网页等）被永久转移到其它URL

404 - 请求的资源（网页等）不存在

500 - 内部服务器错误

## 16、一个页面从输入 URL 到页面加载显示完成，这个过程中都发生了什么？

分为4个步骤：

## 1. 当发送一个 URL 请求时，不管这个 URL 是 Web 页面的 URL 还是 Web 页面上每个资源的 URL，浏览器都会开启一个线程来处理这个请求，同时在远程 DNS 服务器上启动一个 DNS 查询。这能使浏览器获得请求对应的 IP 地址。

## 2. 浏览器与远程 Web 服务器通过 TCP 三次握手协商来建立一个 TCP/IP 连接。该握手包括一个同步报文，一个同步-应答报文和一个应答报文，这三个报文在 浏览器和服务器之间传递。该握手首先由客户端尝试建立起通信，而后服务器应答并接受客户端的请求，最后由客户端发出该请求已经被接受的报文。

## 3. 一旦 TCP/IP 连接建立，浏览器会通过该连接向远程服务器发送 HTTP 的 GET 请求。远程服务器找到资源并使用 HTTP 响应返回该资源，值为 200 的 HTTP 响应状态表示一个正确的响应。

## 4. 此时，Web 服务器提供资源服务，客户端开始下载资源。

## 17、ajax请求的时候get 和post方式的区别

get一般用来进行查询操作，url地址有长度限制，请求的参数都暴露在url地址当中，如果传递中文参数，需要自己进行编码操作，安全性较低。

post请求方式主要用来提交数据，没有数据长度的限制，提交的数据内容存在于http请求体中，数据不会暴漏在url地址中。

## 18、ajax请求时，如何解释json数据

使用eval() 或者JSON.parse() 鉴于安全性考虑，推荐使用JSON.parse()更靠谱，对数据的安全性更好。

## 19、.javascript的本地对象，内置对象和宿主对象

本地对象为独立于宿主环境的ECMAScript提供的对象，包括Array Object RegExp等可以new实例化的对象

内置对象为Gload，Math 等不可以实例化的(他们也是本地对象，内置对象是本地对象的一个子集)

宿主对象为所有的非本地对象，所有的BOM和DOM对象都是宿主对象，如浏览器自带的document,window 等对象

## 20、为什么利用多个域名来存储网站资源会更有效？

确保用户在不同地区能用最快的速度打开网站，其中某个域名崩溃用户也能通过其他郁闷访问网站，并且不同的资源放到不同的服务器上有利于减轻单台服务器的压力。

## 21、请说出三种减低页面加载时间的方法

1、压缩css、js文件
 2、合并js、css文件，减少http请求
 3、外部js、css文件放在最底下
 4、减少dom操作，尽可能用变量替代不必要的dom操作

## 22、HTTP状态码都有那些。

200 OK      //客户端请求成功

400 Bad Request  //客户端请求有语法错误，不能被服务器所理解

403 Forbidden  //服务器收到请求，但是拒绝提供服务

404 Not Found  //请求资源不存在，输入了错误的URL

500 Internal Server Error //服务器发生不可预期的错误

503 Server Unavailable  //服务器当前不能处理客户端的请求，一段时间后可能恢复正常

# 六、JS高级

## 1、 JQuery一个对象可以同时绑定多个事件，这是如何实现的？

jQuery可以给一个对象同时绑定多个事件，低层实现方式是使用addEventListner或attachEvent兼容不同的浏览器实现事件的绑定，这样可以给同一个对象注册多个事件。

## 2、 知道什么是webkit么? 知道怎么用浏览器的各种工具来调试和debug代码么?

Webkit是浏览器引擎，包括html渲染和js解析功能，手机浏览器的主流内核，与之相对应的引擎有Gecko（Mozilla Firefox 等使用）和Trident（也称MSHTML，IE 使用）。 

对于浏览器的调试工具要熟练使用，主要是页面结构分析，后台请求信息查看，js调试工具使用，熟练使用这些工具可以快速提高解决问题的效率

## 3、 如何测试前端代码? 知道BDD, TDD, Unit Test么? 知道怎么测试你的前端工程么(mocha, sinon, jasmin, qUnit..)?

了解BDD行为驱动开发与TDD测试驱动开发已经单元测试相关概念，

**4、**  **前端templating(Mustache, underscore, handlebars)是干嘛的, 怎么用?**

Web 模板引擎是为了使用户界面与业务数据（内容）分离而产生的，

Mustache 是一个 logic-less （轻逻辑）模板解析引擎，它的优势在于可以应用在 Javascript、PHP、Python、Perl 等多种编程语言中。

Underscore封装了常用的JavaScript对象操作方法，用于提高开发效率。

Handlebars 是 JavaScript 一个语义模板库，通过对view和data的分离来快速构建Web模板。

## 5、 简述一下 Handlebars 的基本用法？

没有用过的话说出它是干什么的即可

## 6、 简述一下 Handlerbars 的对模板的基本处理流程， 如何编译的？如何缓存的？

学习技术不仅要会用，还有熟悉它的实现机制，这样在开发中遇到问题时才能更好的解决

## 7、 用js实现千位分隔符?

原生js的熟练度，实践经验，实现思路

## 8、 检测浏览器版本版本有哪些方式？

IE与标准浏览器判断，IE不同版本的判断，userAgent  var ie = /*@cc_on !@*/false;

## 9、 我们给一个dom同时绑定两个点击事件，一个用捕获，一个用冒泡，你来说下会执行几次事件，然后会先执行冒泡还是捕获

对两种事件模型的理解

## 10、实现一个函数clone，可以对JavaScript中的5种主要的数据类型（包括Number、String、Object、Array、Boolean）进行值复制

·    考察点1：对于基本数据类型和引用数据类型在内存中存放的是值还是指针这一区别是否清楚

·    考察点2：是否知道如何判断一个变量是什么类型的

·    考察点3：递归算法的设计

|      | // 方法一：   Object.prototype.clone =   function(){      var o =   this.constructor === Array ? [] : {};      for(var e   in this){         o[e] = typeof this[e] ===   "object" ? this[e].clone() : this[e];      }      return o;   }   //方法二：        /**        *   克隆一个对象        *   @param Obj        *   @returns        */       function   clone(Obj) {              var   buf;              if   (Obj instanceof Array) {                  buf   = [];//创建一个空的数组                var   i = Obj.length;                  while   (i--) {                      buf[i]   = clone(Obj[i]);                  }                    return   buf;               }else   if (Obj instanceof Object){                  buf   = {};//创建一个空对象                for   (var k in Obj) { //为这个对象添加新的属性                    buf[k]   = clone(Obj[k]);                  }                    return   buf;              }else{ //普通变量直接赋值               return   Obj;              }            } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 11、如何消除一个数组里面重复的元素？

|      | var arr=[1,2,3,3,4,4,5,5,6,1,9,3,25,4];           function deRepeat(){               var   newArr=[];               var   obj={};               var   index=0;               var   l=arr.length;               for(var   i=0;i<l;i++){                   if(obj[arr[i]]==undefined)                     {                       obj[arr[i]]=1;                       newArr[index++]=arr[i];                     }                   else   if(obj[arr[i]]==1)                     continue;               }               return   newArr;           }           var   newArr2=deRepeat(arr);           alert(newArr2); //输出1,2,3,4,5,6,9,25 |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 12、小贤是一条可爱的小狗(Dog)，它的叫声很好听(wow)，每次看到主人的时候就会乖乖叫一声(yelp)。从这段描述可以得到以下对象：

|      | function Dog() {         this.wow = function() {                  alert(’Wow’);         }         this.yelp = function() {                 this.wow();         }   } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

小芒和小贤一样，原来也是一条可爱的小狗，可是突然有一天疯了(MadDog)，一看到人就会每隔半秒叫一声(wow)地不停叫唤(yelp)。请根据描述，按示例的形式用代码来实。（继承，原型，setInterval）

|      | function MadDog() {       this.yelp = function() {             var self =   this;                       setInterval(function()   {                   self.wow();                     }, 500);         }   }   MadDog.prototype = new   Dog();            //for test   var dog = new Dog();   dog.yelp();   var madDog = new MadDog();   madDog.yelp(); |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 13、下面这个ul，如何点击每一列的时候alert其index?（闭包）

|      | <ul id="test">   <li>这是第一条</li>   <li>这是第二条</li>   <li>这是第三条</li>   </ul> |
| ---- | ------------------------------------------------------------ |
|      | // 方法一：   var lis=document.getElementById('2223').getElementsByTagName('li');   for(var i=0;i<3;i++)   {       lis[i].index=i;       lis[i].onclick=function(){           alert(this.index);       };   }   //方法二：   var lis=document.getElementById('2223').getElementsByTagName('li');   for(var i=0;i<3;i++){       lis[i].index=i;       lis[i].onclick=(function(a){           return function() {               alert(a);           }       })(i);   } |

## 14、编写一个JavaScript函数，输入指定类型的选择器(仅需支持id，class，tagName三种简单CSS选择器，无需兼容组合选择器)可以返回匹配的DOM节点，需考虑浏览器兼容性和性能。

/*** @param selector {String} 传入的CSS选择器。* @return {Array}*/

|      | var query = function(selector) {   var reg =   /^(#)?(## .)?(## w+)$/img;   var regResult =   reg.exec(selector);   var result = [];   //如果是id选择器   if(regResult[1]) {   if(regResult[3]) {   if(typeof   document.querySelector === "function") {   result.push(document.querySelector(regResult[3]));       }else {         result.push(document.getElementById(regResult[3]));       }      }      }      //如果是class选择器      else if(regResult[2]) {         if(regResult[3])   {          if(typeof   document.getElementsByClassName === 'function') {            var doms =   document.getElementsByClassName(regResult[3]);            if(doms) {               result = converToArray(doms);            }          }        //如果不支持getElementsByClassName函数        else {             var allDoms = document.getElementsByTagName("*") ;          for(var i = 0, len =   allDoms.length; i < len; i++) {            if(allDoms[i].className.search(new   RegExp(regResult[2])) > -1) {              result.push(allDoms[i]);             }          }         }         }   }     //如果是标签选择器     else if(regResult[3]) {       var doms = document.getElementsByTagName(regResult[3].toLowerCase());       if(doms) {         result = converToArray(doms);       }     }     return result;     }     function converToArray(nodes){       var array =   null;                try{                 array = Array.prototype.slice.call(nodes,0);//针对非IE浏览器                   }catch(ex){          array =   new Array();                 for( var i = 0   ,len = nodes.length; i < len ; i++ ) {          array.push(nodes[i])                   }     }           return array;   } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 15、请评价以下代码并给出改进意见。

|      | if(window.addEventListener){       var addListener =   function(el,type,listener,useCapture){           el.addEventListener(type,listener,useCapture);     };   }   else if(document.all){       addListener = function(el,type,listener){           el.attachEvent("on"+type,function(){             listener.apply(el);         });      }     } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

·    　不应该在if和else语句中声明addListener函数，应该先声明；

·    　不需要使用window.addEventListener或document.all来进行检测浏览器，应该使用能力检测；

·    　由于attachEvent在IE中有this指向问题，所以调用它时需要处理一下

改进如下：



## 16、给String对象添加一个方法，传入一个string类型的参数，然后将string的每个字符间价格空格返回，例如：

addSpace(“hello world”) // -> ‘h e l l o  w o r l d’

|      | String.prototype.spacify =   function(){         return this.split('').join(' ');       }; |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

接着上述问题答案提问，1）直接在对象的原型上添加方法是否安全？尤其是在Object对象上。(这个我没能答出？希望知道的说一下。)　2）函数声明与函数表达式的区别？

答案：在js中，解析器在向执行环境中加载数据时，对函数声明和函数表达式并非是一视同仁的，解析器会率先读取函数声明，并使其在执行任何代码之前可用（可以访问），至于函数表达式，则必须等到解析器执行到它所在的代码行，才会真正被解析执行。

## 17、定义一个log方法，让它可以代理console.log的方法。

可行的方法一：



如果要传入多个参数呢？显然上面的方法不能满足要求，所以更好的方法是：



到此，追问apply和call方法的异同。

对于apply和call两者在作用上是相同的，即是调用一个对象的一个方法，以另一个对象替换当前对象。将一个函数的对象上下文从初始的上下文改变为由 thisObj 指定的新对象。

但两者在参数上有区别的。对于第一个参数意义都一样，但对第二个参数： apply传入的是一个参数数组，也就是将多个参数组合成为一个数组传入，而call则作为call的参数传入（从第二个参数开始）。 如 func.call(func1,var1,var2,var3)对应的apply写法为：func.apply(func1,[var1,var2,var3]) 。

## 18、在Javascript中什么是伪数组？如何将伪数组转化为标准数组？

伪数组（类数组）：无法直接调用数组方法或期望length属性有什么特殊的行为，但仍可以对真正数组遍历方法来遍历它们。典型的是函数的argument参数，还有像调用getElementsByTagName,document.childNodes之类的,它们都返回NodeList对象都属于伪数组。可以使用Array.prototype.slice.call(fakeArray)将数组转化为真正的Array对象。

假设接第八题题干，我们要给每个log方法添加一个”(app)”前缀，比如’hello world!’ ->’(app)hello world!’。方法如下：



## 19、对作用域上下文和this的理解，看下列代码：



问两处console输出什么？为什么？

答案是1和undefined。

func是在winodw的上下文中被执行的，所以会访问不到count属性。

继续追问，那么如何确保Uesr总是能访问到func的上下文，即正确返回1。正确的方法是使用Function.prototype.bind。兼容各个浏览器完整代码如下：



## 20、原生JS的window.onload与Jquery的$(document).ready(function(){})有什么不同？如何用原生JS实现Jq的ready方法？

window.onload()方法是必须等到页面内包括图片的所有元素加载完毕后才能执行。

$(document).ready()是DOM结构绘制完毕后就执行，不必等到加载完毕。



如果上述代码十分难懂，下面这个简化版：



## 21、（设计题）想实现一个对页面某个节点的拖曳？如何做？（使用原生JS）

回答出概念即可，下面是几个要点

## 1. 给需要拖拽的节点绑定mousedown, mousemove, mouseup事件

## 2. mousedown事件触发后，开始拖拽

## 3. mousemove时，需要通过event.clientX和clientY获取拖拽位置，并实时更新位置

## 4. mouseup时，拖拽结束

## 5. 需要注意浏览器边界的情况

## 22、请实现如下功能

[![171232302169311](file://localhost/Users/stav/Library/Group%20Containers/UBF8T346G9.Office/msoclip1/01/clip_image002.gif)](http://jbcdn2.b0.upaiyun.com/2014/10/a2e3bf5eab2f56af1010d2d0153ed19d.png)



## 23、说出以下函数的作用是？空白区域应该填写什么？



答案：访函数的作用是使用format函数将函数的参数替换掉{0}这样的内容，返回一个格式化后的结果：

第一个空是：arguments

第二个空是：/## {(## d+)## }/ig

## 24、 Javascript作用链域?

理解变量和函数的访问范围和生命周期，全局作用域与局部作用域的区别，JavaScript中没有块作用域，函数的嵌套形成不同层次的作用域，嵌套的层次形成链式形式，通过作用域链查找属性的规则需要深入理解。

## 25、 谈谈This对象的理解。

理解不同形式的函数调用方式下的this指向，理解事件函数、定时函数中的this指向，函数的调用形式决定了this的指向。

## 26、 eval是做什么的？

它的功能是把对应的字符串解析成JS代码并运行；应该避免使用eval，不安全，非常耗性能（2个步骤，一次解析成js语句，一次执行）

 

## 27、 关于事件，IE与火狐的事件机制有什么区别？ 如何阻止冒泡？

[1].在IE中,事件对象是作为一个全局变量来保存和维护的.所有的浏览器事件,不管是用户触发的，还是其他事件,都会更新window.event对象.所以在代码中，只要调用window.event就可以获取事件对象， 再event.srcElement就可以取得触发事件的元素进行进一步处理. 

[2].在FireFox中，事件对象却不是全局对象，一般情况下，是现场发生，现场使用，FireFox把事件对象自动传给事件处理程序.

关于事件的兼容性处理要熟练掌握，事件对象具体哪些属性存在兼容性问题，IE与标准事件模型事件冒泡与事件捕获的支持要理解

## 28、 什么是闭包（closure），为什么要用它？

简单的理解是函数的嵌套形成闭包，闭包包括函数本身已经它的外部作用域

使用闭包可以形成独立的空间，延长变量的生命周期，报存中间状态值

## 29、javascript 代码中的"use strict";是什么意思 ? 使用它区别是什么？

意思是使用严格模式，使用严格模式，一些不规范的语法将不再支持

## 30、如何判断一个对象是否属于某个类？

Instanceof   constructor

## 31、new操作符具体干了什么呢?

1、创建一个空对象，并且 this 变量引用该对象，同时还继承了该函数的原型。

  2、属性和方法被加入到 this 引用的对象中。

  3、新创建的对象由 this 所引用，并且最后隐式的返回 this 。

## 32、用原生JavaScript的实现过什么功能吗？

主要考察原生js的实践经验

## 33、Javascript中，有一个函数，执行时对象查找时，永远不会去查找原型，这个函数是？

HasOwnProperty

## 34、对JSON的了解？

轻量级数据交互格式，可以形成复杂的嵌套格式，解析非常方便

## 35、js延迟加载的方式有哪些？

方案一：<script>标签的async="async"属性（详细参见：script标签的async属性）

方案二：<script>标签的defer="defer"属性

方案三：动态创建<script>标签

方案四：AJAX eval（使用AJAX得到脚本内容，然后通过eval_r(xmlhttp.responseText)来运行脚本）

方案五：iframe方式

## 36、模块化开发怎么做？

理解模块化开发模式：浏览器端requirejs，seajs；服务器端nodejs；ES6模块化；fis、webpack等前端整体模块化解决方案；grunt、gulp等前端工作流的使用

## 37、AMD（Modules/Asynchronous-Definition）、CMD（Common Module Definition）规范区别？

理解这两种规范的差异，主要通过requirejs与seajs的对比，理解模块的定义与引用方式的差异以及这两种规范的设计原则

## 38、requireJS的核心原理是什么？（如何动态加载的？如何避免多次加载的？如何 缓存的？）

核心是js的加载模块，通过正则匹配模块以及模块的依赖关系，保证文件加载的先后顺序，根据文件的路径对加载过的文件做了缓存

## 39、让你自己设计实现一个requireJS，你会怎么做？

核心是实现js的加载模块，维护js的依赖关系，控制好文件加载的先后顺序

## 40、谈一谈你对ECMAScript6的了解？

ES6新的语法糖，类，模块化等新特性

## 41、ECMAScript6 怎么写class么，为什么会出现class这种东西?

class Point {

  constructor(x, y) {

    this.x = x;
    
    this.y = y;

  }

  toString() {

     return '('+this.x+', '+this.y+')';

  }

}

## 42、异步加载的方式有哪些？

方案一：<script>标签的async="async"属性（详细参见：script标签的async属性）

方案二：<script>标签的defer="defer"属性

方案三：动态创建<script>标签

方案四：AJAX eval（使用AJAX得到脚本内容，然后通过eval_r(xmlhttp.responseText)来运行脚本）

方案五：iframe方式

## 43、documen.write和 innerHTML的区别?

document.write是重写整个document, 写入内容是字符串的html

innerHTML是HTMLElement的属性，是一个元素的内部html内容

## 44、DOM操作——怎样添加、移除、移动、复制、创建和查找节点?

（1）创建新节点

      createDocumentFragment()    //创建一个DOM片段
    
      createElement_x()   //创建一个具体的元素
    
      createTextNode()   //创建一个文本节点

（2）添加、移除、替换、插入

      appendChild()
    
      removeChild()
    
      replaceChild()
    
      insertBefore()

（3）查找

      getElementsByTagName()    //通过标签名称
    
      getElementsByName()    //通过元素的Name属性的值
    
      getElementById()    //通过元素Id，唯一性

## 45、call() 和 .apply() 的含义和区别？

apply的参数是数组形式，call的参数是单个的值，除此之外在使用上没有差别，重点理解这两个函数调用的this改变

## 46、数组和对象有哪些原生方法，列举一下？

Array.concat( ) 连接数组 

Array.join( ) 将数组元素连接起来以构建一个字符串 

Array.length 数组的大小 

Array.pop( ) 删除并返回数组的最后一个元素 

Array.push( ) 给数组添加元素 

Array.reverse( ) 颠倒数组中元素的顺序 

Array.shift( ) 将元素移出数组 

Array.slice( ) 返回数组的一部分 

Array.sort( ) 对数组元素进行排序 

Array.splice( ) 插入、删除或替换数组的元素 

Array.toLocaleString( ) 把数组转换成局部字符串 

Array.toString( ) 将数组转换成一个字符串 

Array.unshift( ) 在数组头部插入一个元素

 

Object.hasOwnProperty( ) 检查属性是否被继承 

Object.isPrototypeOf( ) 一个对象是否是另一个对象的原型 

Object.propertyIsEnumerable( ) 是否可以通过for/in循环看到属性 

Object.toLocaleString( ) 返回对象的本地字符串表示 

Object.toString( ) 定义一个对象的字符串表示 

Object.valueOf( ) 指定对象的原始值

## 47、JS 怎么实现一个类。怎么实例化这个类

严格来讲js中并没有类的概念，不过js中的函数可以作为构造函数来使用，通过new来实例化，其实函数本身也是一个对象。

## 48、JavaScript中的作用域与变量声明提升？

理解JavaScript的预解析机制，js的运行主要分两个阶段：js的预解析和运行，预解析阶段所有的变量声明和函数定义都会提前，但是变量的赋值不会提前

## 49、如何编写高性能的Javascript？

使用 DocumentFragment 优化多次 append

通过模板元素 clone ，替代 createElement

使用一次 innerHTML 赋值代替构建 dom 元素

使用 firstChild 和 nextSibling 代替 childNodes 遍历 dom 元素 

使用 Array 做为 StringBuffer ，代替字符串拼接的操作 

将循环控制量保存到局部变量

顺序无关的遍历时，用 while 替代 for

将条件分支，按可能性顺序从高到低排列

在同一条件子的多（ >2 ）条件分支时，使用 switch 优于 if

使用三目运算符替代条件分支 

需要不断执行的时候，优先考虑使用 setInterval

## 50、那些操作会造成内存泄漏？

闭包，循环

## 51、javascript对象的几种创建方式？

## 1. 工厂模式

## 2. 构造函数模式

## 3. 原型模式

## 4. 混合构造函数和原型模式

## 5. 动态原型模式

## 6. 寄生构造函数模式

## 7. 稳妥构造函数模式

## 52、javascript继承的 6 种方法？

## 1. 原型链继承

## 2. 借用构造函数继承

## 3. 组合继承(原型+借用构造)

## 4. 原型式继承

## 5. 寄生式继承

## 6. 寄生组合式继承

53、eval是做什么的？

## 1. 它的功能是把对应的字符串解析成JS代码并运行

## 2. 应该避免使用eval，不安全，非常耗性能（2次，一次解析成js语句，一次执行）

## 54、JavaScript 原型，原型链 ? 有什么特点？

## 1. 原型对象也是普通的对象，是对象一个自带隐式的 __proto__ 属性，原型也有可能有自己的原型，如果一个原型对象的原型不为 null 的话，我们就称之为原型链

## 2. 原型链是由一些用来继承和共享属性的对象组成的（有限的）对象链

## 55、事件、IE与火狐的事件机制有什么区别？ 如何阻止冒泡？

## 1. 我们在网页中的某个操作（有的操作对应多个事件）。例如：当我们点击一个按钮就会产生一个事件。是可以被 JavaScript 侦测到的行为

## 2. 事件处理机制：IE是事件冒泡、firefox同时支持两种事件模型，也就是：捕获型事件和冒泡型事件

## 3. ev.stopPropagation();

注意旧ie的方法：ev.cancelBubble = true;

## 56、简述一下Sass、Less，且说明区别？

他们是动态的样式语言，是CSS预处理器,CSS上的一种抽象层。他们是一种特殊的语法/语言而编译成CSS。

变量符不一样，less是@，而Sass是$;

Sass支持条件语句，可以使用if{}else{},for{}循环等等。而Less不支持;

Sass是基于Ruby的，是在服务端处理的，而Less是需要引入less.js来处理Less代码输出Css到浏览器

## 57、关于javascript中apply()和call()方法的区别？

相同点:两个方法产生的作用是完全一样的

不同点:方法传递的参数不同

Object.call(this,obj1,obj2,obj3)

Object.apply(this,arguments)

apply()接收两个参数，一个是函数运行的作用域(this)，另一个是参数数组。

call()方法第一个参数与apply()方法相同，但传递给函数的参数必须列举出来。

## 58、简述一下JS中的闭包？

闭包用的多的两个作用：读取函数内部的变量值；让这些变量值始终保存着(在内存中)。

同时需要注意的是：闭包慎用，不滥用，不乱用，由于函数内部的变量都被保存在内存中，会导致内存消耗大。

## 59、说说你对this的理解？

在JavaScript中，this通常指向的是我们正在执行的函数本身，或者是，指向该函数所属的对象。

全局的this → 指向的是Window

函数中的this → 指向的是函数所在的对象

对象中的this → 指向其本身

## 60、分别阐述split(),slice(),splice(),join()？

join()用于把数组中的所有元素拼接起来放入一个字符串。所带的参数为分割字符串的分隔符，默认是以逗号分开。归属于Array

split()即把字符串分离开，以数组方式存储。归属于Stringstring

slice() 方法可从已有的数组中返回选定的元素。该方法并不会修改数组，而是返回一个子数组。如果想删除数组中的一段元素，应该使用方法 Array.splice()

splice() 方法向/从数组中添加/删除项目，然后返回被删除的项目。返回的是含有被删除的元素的数组。

## 61、事件委托是什么？

让利用事件冒泡的原理，让自己的所触发的事件，让他的父元素代替执行！

## 62、如何阻止事件冒泡和默认事件？

阻止浏览器的默认行为

window.event?window.event.returnValue=false:e.preventDefault();

停止事件冒泡

window.event?window.event.cancelBubble=true:e.stopPropagation();

原生JavaScript中，return false;只阻止默认行为，不阻止冒泡，jQuery中的return false;既阻止默认行为，又阻止冒泡

## 63、添加 删除 替换 插入到某个接点的方法？

obj.appendChidl()

obj.removeChild()

obj.replaceChild()

obj.innersetBefore() 

## 64、你用过require.js吗？它有什么特性？

（1）实现js文件的异步加载，避免网页失去响应；

（2）管理模块之间的依赖性，便于代码的编写和维护。

## 65、谈一下JS中的递归函数，并且用递归简单实现阶乘？

递归即是程序在执行过程中不断调用自身的编程技巧，当然也必须要有一个明确的结束条件，不然就会陷入死循环。

## 66、请用正则表达式写一个简单的邮箱验证。

/^[a-zA-Z0-9_-]+@[a-zA-Z0-9_-]+(## .[a-zA-Z0-9_-]+)+$/;

## 67、简述一下你对web性能优化的方案？

    1、尽量减少 HTTP 请求

2、使用浏览器缓存

3、使用压缩组件

4、图片、JS的预载入

5、将脚本放在底部

6、将样式文件放在页面顶部

7、使用外部的JS和CSS

8、精简代码

## 68、在JS中有哪些会被隐式转换为false

Undefined、null、关键字false、NaN、零、空字符串

## 69、定时器setInterval有一个有名函数fn1，setInterval（fn1,500）与setInterval（fn1(),500）有什么区别？

第一个是重复执行每500毫秒执行一次，后面一个只执行一次。

## 70、外部JS文件出现中文字符，会出现什么问题，怎么解决？

会出现乱码，加charset=”GB2312”;

## 71、谈谈浏览器的内核，并且说一下什么是内核？

Trident (['traɪd(ə)nt])--IE，Gecko (['gekəʊ])--Firefox, Presto (['prestəʊ])--opera,webkit—谷歌和Safari

浏览器内核又可以分成两部分：渲染引擎和 JS 引擎。它负责取得网页的内容（HTML、XML、图像等等）、整理讯息（例如加入 CSS 等），以及计算网页的显示方式，然后会输出至显示器或打印机。JS 引擎则是解析 Javascript 语言，执行 javascript 语言来实现网页的动态效果。

## 72、JavaScript原型，原型链 ? 有什么特点？

## *  原型对象也是普通的对象，是对象一个自带隐式的 __proto__ 属性，原型也有可能有自己的原型，如果一个原型对象的原型不为null的话，我们就称之为原型链。

## *  原型链是由一些用来继承和共享属性的对象组成的（有限的）对象链。

## * JavaScript的数据对象有那些属性值？

　　writable：这个属性的值是否可以改。

　　configurable：这个属性的配置是否可以删除，修改。

　　enumerable：这个属性是否能在for…in循环中遍历出来或在Object.keys中列举出来。

　　value：属性值。

## * 当我们需要一个属性的时，Javascript引擎会先看当前对象中是否有这个属性， 如果没有的话，就会查找他的Prototype对象是否有这个属性。

 function clone(proto) {

　　function Dummy() { }

　　Dummy.prototype = proto;

　　Dummy.prototype.constructor = Dummy;

　　return new Dummy(); //等价于Object.create(Person);

 } 

        function object(old) {
    
         function F() {};
    
         F.prototype = old;
    
         return new F();
    
        }
    
    var newObj = object(oldObject);

## 73、写一个通用的事件侦听器函数

`// event(事件)工具集，来源：https://github.com/markyun

markyun.Event = {

    // 页面加载完成后
    
    readyEvent : function(fn) {
    
        if (fn==null) {
    
            fn=document;
    
        }
    
        var oldonload = window.onload;
    
        if (typeof window.onload != 'function') {
    
            window.onload = fn;
    
        } else {
    
            window.onload = function() {
    
                oldonload();
    
                fn();
    
            };
    
        }
    
    },
    
    // 视能力分别使用dom0||dom2||IE方式 来绑定事件
    
    // 参数： 操作的元素,事件名称 ,事件处理程序
    
    addEvent : function(element, type, handler) {
    
        if (element.addEventListener) {
    
            //事件类型、需要执行的函数、是否捕捉
    
            element.addEventListener(type, handler, false);
    
        } else if (element.attachEvent) {
    
            element.attachEvent('on' + type, function() {
    
                handler.call(element);
    
            });
    
        } else {
    
            element['on' + type] = handler;
    
        }
    
    },
    
    // 移除事件
    
    removeEvent : function(element, type, handler) {
    
        if (element.removeEnentListener) {
    
            element.removeEnentListener(type, handler, false);
    
        } else if (element.datachEvent) {
    
            element.detachEvent('on' + type, handler);
    
        } else {
    
            element['on' + type] = null;
    
        }
    
    }, 
    
    // 阻止事件 (主要是事件冒泡，因为IE不支持事件捕获)
    
    stopPropagation : function(ev) {
    
        if (ev.stopPropagation) {
    
            ev.stopPropagation();
    
        } else {
    
            ev.cancelBubble = true;
    
        }
    
    },
    
    // 取消事件的默认行为
    
    preventDefault : function(event) {
    
        if (event.preventDefault) {
    
            event.preventDefault();
    
        } else {
    
            event.returnValue = false;
    
        }
    
    },
    
    // 获取事件目标
    
    getTarget : function(event) {
    
        return event.target || event.srcElement;
    
    },
    
    // 获取event对象的引用，取到事件的所有信息，确保随时能使用event；
    
    getEvent : function(e) {
    
        var ev = e || window.event;
    
        if (!ev) {
    
            var c = this.getEvent.caller;
    
            while (c) {
    
                ev = c.arguments[0];
    
                if (ev && Event == ev.constructor) {
    
                    break;
    
                }
    
                c = c.caller;
    
            }
    
        }
    
        return ev;
    
    }

}; 

## 74、事件、IE与火狐的事件机制有什么区别？ 如何阻止冒泡？

 ## 1. 我们在网页中的某个操作（有的操作对应多个事件）。例如：当我们点击一个按钮就会产生一个事件。是可以被 JavaScript 侦测到的行为。  

 ## 2. 事件处理机制：IE是事件冒泡、火狐是 事件捕获；

 ## 3.  ev.stopPropagation();

## 75、什么是闭包（closure），为什么要用？

执行say667()后,say667()闭包内部变量会存在,而闭包内部函数的内部变量不会存在.使得Javascript的垃圾回收机制GC不会收回say667()所占用的资源，因为say667()的内部函数的执行需要依赖say667()中的变量。这是对闭包作用的非常直白的描述.

  function say667() {

    // Local variable that ends up within closure
    
    var num = 666;
    
    var sayAlert = function() { alert(num); }
    
    num++;
    
    return sayAlert;

}

 var sayAlert = say667();

 sayAlert()//执行结果应该弹出的667  

## 76、如何判断一个对象是否属于某个类？

使用instanceof （待完善）

if(a instanceof Person){

    alert('yes');

}

## 77、new操作符具体干了什么呢?

  1、创建一个空对象，并且 this 变量引用该对象，同时还继承了该函数的原型。

  2、属性和方法被加入到 this 引用的对象中。

  3、新创建的对象由 this 所引用，并且最后隐式的返回 this 。

    var obj  = {};
    
    obj.__proto__ = Base.prototype;
    
    Base.call(obj); 

## 78、JSON 的了解

JSON(JavaScript Object Notation) 是一种轻量级的数据交换格式。它是基于JavaScript的一个子集。数据格式简单, 易于读写, 占用带宽小

{'age':'12', 'name':'back'}

## 79、js延迟加载的方式有哪些

defer和async、动态创建DOM方式（用得最多）、按需异步载入js

## 80、模块化怎么做？

立即执行函数,不暴露私有成员

var module1 = (function(){

　　　　var _count = 0;

　　　　var m1 = function(){

　　　　　　//...

　　　　};

　　　　var m2 = function(){

　　　　　　//...

　　　　};

　　　　return {

　　　　　　m1 : m1,

　　　　　　m2 : m2

　　　　};

　　})(); 

## 81、异步加载的方式

  (1) defer，只支持IE

  (2) async：

  (3) 创建script，插入到DOM中，加载完毕后callBack

      documen.write和 innerHTML的区别
    
      document.write只能重绘整个页面
    
      innerHTML可以重绘页面的一部分

## 82、告诉我答案是多少？

(function(x){

    delete x;
    
    alert(x);

})(1+5);

函数参数无法delete删除，delete只能删除通过for in访问的属性。

当然，删除失败也不会报错，所以代码运行会弹出“1”。

## 83、JS中的call()和apply()方法的区别？

例子中用 add 来替换 sub，add.call(sub,3,1) == add(3,1) ，所以运行结果为：alert(4);

注意：js 中的函数其实是对象，函数名是对 Function 对象的引用。

function add(a,b){

    alert(a+b);

}

function sub(a,b){

    alert(a-b);

}

add.call(sub,3,1);  

## 84、Jquery与jQuery UI 有啥区别？

*jQuery是一个js库，主要提供的功能是选择器，属性修改和事件绑定等等。

*jQuery UI则是在jQuery的基础上，利用jQuery的扩展性，设计的插件。

提供了一些常用的界面元素，诸如对话框、拖动行为、改变大小行为等等

## 85、jquery 中如何将数组转化为json字符串，然后再转化回来？

jQuery中没有提供这个功能，所以你需要先编写两个jQuery的扩展：

    $.fn.stringifyArray = function(array) {
    
        return JSON.stringify(array)
    
    }
    
    $.fn.parseArray = function(array) {
    
        return JSON.parse(array)
    
    } 
    
    然后调用：
    
    $("").stringifyArray(array)

## 86、JavaScript中的作用域与变量声明提升？

其他部分

（HTTP、正则、优化、重构、响应式、移动端、团队协作、SEO、UED、职业生涯）

    *基于Class的选择性的性能相对于Id选择器开销很大，因为需遍历所有DOM元素。
    
    *频繁操作的DOM，先缓存起来再操作。用Jquery的链式调用更好。   
    
     比如：var str=$("a").attr("href");
    
    *for (var i = size; i < arr.length; i++) {}
    
     for 循环每一次循环都查找了数组 (arr) 的.length 属性，在开始循环的时候设置一个变量来存储这个数字，可以让循环跑得更快： 
    
     for (var i = size, length = arr.length; i < length; i++) {}

## 87、前端开发的优化问题（看雅虎14条性能优化原则）。

  （1） 减少http请求次数：CSS Sprites, JS、CSS源码压缩、图片大小控制合适；网页Gzip，CDN托管，data缓存 ，图片服务器。

  （2） 前端模板 JS+数据，减少由于HTML标签导致的带宽浪费，前端用变量保存AJAX请求结果，每次操作本地变量，不用请求，减少请求次数

  （3） 用innerHTML代替DOM操作，减少DOM操作次数，优化javascript性能。

  （4） 当需要设置的样式很多时设置className而不是直接操作style。

  （5） 少用全局变量、缓存DOM节点查找的结果。减少IO读取操作。

  （6） 避免使用CSS Expression（css表达式)又称Dynamic properties(动态属性)。

  （7） 图片预加载，将样式表放在顶部，将脚本放在底部  加上时间戳。

  （8） 避免在页面的主体布局中使用table，table要等其中的内容完全下载之后才会显示出来，显示比div+css布局慢。

## 88、http状态码有那些？分别代表是什么意思？

    100-199 用于指定客户端应相应的某些动作。 
    
    200-299 用于表示请求成功。 
    
    300-399 用于已经移动的文件并且常被包含在定位头信息中指定新的地址信息。 

400-499 用于指出客户端的错误。

400  语义有误，当前请求无法被服务器理解。

401  当前请求需要用户验证 

403  服务器已经理解请求，但是拒绝执行它。

500-599 用于支持服务器错误。 

503 – 服务不可用

## 89、一个页面从输入 URL 到页面加载显示完成，这个过程中都发生了什么？（流程说的越详细越好）

    要熟悉前后端的通信流程，最好把动态网站的背后细节也介绍一遍

# 七、流行框架

## 1、JQuery的源码看过吗？能不能简单概况一下它的实现原理？

考察学习知识的态度，是否仅仅是停留在使用层面，要知其然知其所以然

## 2、jQuery.fn的init方法返回的this指的是什么对象？为什么要返回this？

this执行init构造函数自身，其实就是jQuery实例对象，返回this是为了实现jQuery的链式操作

## 3、 jquery中如何将数组转化为json字符串，然后再转化回来？

$.parseJSON('{"name":"John"}');

## 4、 jQuery 的属性拷贝(extend)的实现原理是什么，如何实现深拷贝？

递归赋值

## 5、 jquery.extend 与 jquery.fn.extend的区别？

Jquery.extend用来扩展jQuery对象本身；jquery.fn.extend用来扩展jQuery实例

## 6、谈一下Jquery中的bind(),live(),delegate(),on()的区别？

## 7、JQuery一个对象可以同时绑定多个事件，这是如何实现的？

可以同时绑定多个事件，低层实现原理是使用addEventListner与attachEvent兼容处理做事件注册

## 10、     Jquery与jQuery UI有啥区别？

jQuery是操作dom的框架，jQueryUI是基于jQuery做的一个UI组件库

## 11、     jQuery和Zepto的区别？各自的使用场景？

jQuery主要用于pc端，当然有对应的jQuerymobile用于移动端，zepto比jQuery更加小巧，主要用于移动端

## 12、     针对 jQuery 的优化方法？

优先使用ID选择器

在class前使用tag(标签名)

给选择器一个上下文

慎用 .live()方法（应该说尽量不要使用）

使用data()方法存储临时变量

## 13、     Zepto的点透问题如何解决？

点透主要是由于两个div重合，例如：一个div调用show()，一个div调用hide()；这个时候当点击上面的div的时候就会影响到下面的那个div；

解决办法主要有2种：

1.github上有一个叫做fastclick的库，它也能规避移动设备上click事件的延迟响应，https://github.com/ftlabs/fastclick

将它用script标签引入页面（该库支持AMD，于是你也可以按照AMD规范，用诸如require.js的模块加载器引入），并且在dom ready时初始化在body上，

2.根据分析，如果不引入其它类库，也不想自己按照上述fastclcik的思路再开发一套东西，需要1.一个优先于下面的“divClickUnder”捕获的事件；2.并且通过这个事件阻止掉默认行为（下面的“divClickUnder”对click事件的捕获，在ios的safari，click的捕获被认为和滚屏、点击输入框弹起键盘等一样，是一种浏览器默认行为，即可以被event.preventDefault()阻止的行为）。

## 14、知道各种JS框架(Angular, Backbone, Ember, React, Meteor, Knockout...)么? 能讲出他们各自的优点和缺点么?

知识面的宽度，流行框架要多多熟悉

## 15、Underscore 对哪些 JS 原生对象进行了扩展以及提供了哪些好用的函数方法？

Underscore的熟悉程度

## 16、使用过angular吗？angular中的过滤器是干什么用的

在表达式中转换数据<p>姓名为 {{ lastName | uppercase }}</p>

currency，是什么过滤器——格式化数字为货币格式，单位是$符。

 

# 八、移动APP开发

## 1、移动端最小触控区域是多大？

移动端的点击事件的有延迟，时间是多久，为什么会有？ 怎么解决这个延时？（click 有 300ms 延迟,为了实现safari的双击事件的设计，浏览器要知道你是不是要双击操作。）

# 九、NodeJs

## 1.      对Node的优点和缺点提出了自己的看法：

*（优点）因为Node是基于事件驱动和无阻塞的，所以非常适合处理并发请求，

因此构建在Node上的代理服务器相比其他技术实现（如Ruby）的服务器表现要好得多。

此外，与Node代理服务器交互的客户端代码是由javascript语言编写的，

因此客户端和服务器端都用同一种语言编写，这是非常美妙的事情。

*（缺点）Node是一个相对新的开源项目，所以不太稳定，它总是一直在变，

而且缺少足够多的第三方库支持。看起来，就像是Ruby/Rails当年的样子。

## 2.      需求：实现一个页面操作不会整页刷新的网站，并且能在浏览器前进、后退时正确响应。给出你的技术实现方案？

至少给出自己的思路（url-hash,可以使用已有的一些框架history.js等）

## 3.      Node.js的适用场景？

1)、实时应用：如在线聊天，实时通知推送等等（如socket.io）

2)、分布式应用：通过高效的并行I/O使用已有的数据

3)、工具类应用：海量的工具，小到前端压缩部署（如grunt），大到桌面图形界面应用程序

4)、游戏类应用：游戏领域对实时和并发有很高的要求（如网易的pomelo框架）

5)、利用稳定接口提升Web渲染能力

6)、前后端编程语言环境统一：前端开发人员可以非常快速地切入到服务器端的开发（如著名的纯Javascript全栈式MEAN架构）

## 4.      (如果会用node)知道route, middleware, cluster, nodemon, pm2, server-side rendering么?

Nodejs相关概念的理解程度

## 5.      解释一下 Backbone 的 MVC 实现方式？

流行的MVC架构模式

## 6.      什么是“前端路由”?什么时候适合使用“前端路由”? “前端路由”有哪些优点和缺点?

熟悉前后端通信相关知识

## 7.      对Node的优点和缺点提出了自己的看法？

优点：

## 1. 因为Node是基于事件驱动和无阻塞的，所以非常适合处理并发请求，因此构建在Node上的代理服务器相比其他技术实现（如Ruby）的服务器表现要好得多。

## 2. 与Node代理服务器交互的客户端代码是由javascript语言编写的，因此客户端和服务器端都用同一种语言编写，这是非常美妙的事情。

缺点：

## 1. Node是一个相对新的开源项目，所以不太稳定，它总是一直在变。

## 2. 缺少足够多的第三方库支持。看起来，就像是Ruby/Rails当年的样子（第三方库现在已经很丰富了，所以这个缺点可以说不存在了）。

 

# 十、前端概括性问题

## 8.      常使用的库有哪些？常用的前端开发工具？开发过什么应用或组件？

使用率较高的框架有jQuery、YUI、Prototype、Dojo、Ext.js、Mootools等。尤其是jQuery，超过91%。

轻量级框架有Modernizr、underscore.js、backbone.js、Raphael.js等。（理解这些框架的功能、性能、设计原理）

前端开发工具：Sublime Text 、Eclipse、Notepad、Firebug、HttpWatch、Yslow。

开发过的插件：城市选择插件，汽车型号选择插件、幻灯片插件。弹出层。（写过开源程序，加载器，js引擎更好）

## 9.      对BFC规范的理解？ 

Formatting Context：指页面中的一个渲染区域，并且拥有一套渲染规则，他决定了其子元素如何定位，以及与其他元素的相互关系和作用。

## 10.   99%的网站都需要被重构是那本书上写的？

网站重构：应用web标准进行设计（第2版）

## 11.   WEB应用从服务器主动推送Data到客户端有那些方式？

    html5 websoket
    
    WebSocket通过Flash
    
    XHR长时间连接
    
    XHR Multipart Streaming
    
    不可见的Iframe

<script>标签的长时间连接(可跨域)

## 12.   加班的看法

加班就像借钱，原则应当是------救急不救穷

## 13.   平时如何管理你的项目，如何设计突发大规模并发架构？

先期团队必须确定好全局样式（globe.css），编码模式(utf-8) 等

编写习惯必须一致（例如都是采用继承式的写法，单样式都写成一行）；

标注样式编写人，各模块都及时标注（标注关键样式调用的地方）；

页面进行标注（例如 页面 模块 开始和结束）；

CSS跟HTML 分文件夹并行存放，命名都得统一（例如style.css）

JS 分文件夹存放 命民以该JS 功能为准英文翻译；

图片采用整合的 images.png png8 格式文件使用 尽量整合在一起使用方便将来的管理

## 14.   那些操作会造成内存泄漏？

内存泄漏指任何对象在您不再拥有或需要它之后仍然存在。

垃圾回收器定期扫描对象，并计算引用了每个对象的其他对象的数量。如果一个对象的引用数量为 0（没有其他对象引用过该对象），或对该对象的惟一引用是循环的，那么该对象的内存即可回收。

setTimeout 的第一个参数使用字符串而非函数的话，会引发内存泄漏。

闭包、控制台日志、循环（在两个对象彼此引用且彼此保留时，就会产生一个循环）

## 15.   你说你热爱前端，那么应该WEB行业的发展很关注吧？ 说说最近最流行的一些东西吧？

Node.js、Mongodb、npm、MVVM、MEAN、react、angularjs

## 16.   你有了解我们公司吗？说说你的认识？

因为我想去阿里，所以我针对阿里的说

最羡慕就是在双十一购物节，350.19亿元，每分钟支付79万笔。海量数据，居然无一漏单、无一故障。太厉害了。

## 17.   移动端（比如：Android IOS）怎么做好用户体验?

融入自己的设计理念，注重用户体验，选择合适的技术

## 18.   你所知道的页面性能优化方法有那些？

压缩、合并，减少请求，代码层析优化。。。

## 19.   除了前端以外还了解什么其它技术么？你最最厉害的技能是什么？

知识面宽度，最好熟悉一些后台语言，比如php，展现出自己的技术两点

## 20.   AMD（Modules/Asynchronous-Definition）、CMD（Common Module Definition）规范区别？

## 21.   谈谈你认为怎样做能使项目做的更好？

考虑问题的深入，不仅仅停留在完成任务上，要精益求精

## 22.   你对前端界面工程师这个职位是怎么样理解的？它的前景会怎么样？

表现出对前端的认同与兴趣，关注相关技术前沿

## 23.   php中下面哪个函数可以打开一个文件，以对文件进行读和写操作？

A.fget();  B.file_open();  **C.fopen();**  D.open_file();

## 24.   php中rmdir可以直接删除文件夹吗？该目录必须是空的，而且要有相应的权限--来自api

A.任何文件夹都可以删除           B.空文件夹可以删除

C.有权限的任何文件夹都可以删除   D.有权限的空文件夹可以删除

## 25.   phpinset和empty的区别，举例说明

1、empty函数 

用途：检测变量是否为空

判断：如果 var 是非空或非零的值，则 empty() 返回 FALSE。换句话说，""、0、"0"、NULL、FALSE、array()、var $var; 以及没有任何属性的对象都将被认为是空的，如果 var 为空，则返回 TRUE。注意：empty() 只检测变量，检测任何非变量的东西都将导致解析错误。换句话说，后边的语句将不会起作用;

2、isset函数

用途：检测变量是否设置

判断：检测变量是否设置，并且不是 NULL。如果已经使用 unset() 释放了一个变量之后，它将不再是 isset()。若使用 isset() 测试一个被设置成 NULL 的变量，将返回 FALSE。同时要注意的是一个NULL 字节（"## 0"）并不等同于 PHP 的 NULL 常数。

## 26.   php中$_SERVER变量中如何得到当前执行脚本路劲

![http://www.phpddt.com/usr/uploads/2014/03/2709675141.png](file://localhost/Users/stav/Library/Group%20Containers/UBF8T346G9.Office/msoclip1/01/clip_image004.gif)

## 27.   写一个php函数，要求两个日期字符串的天数差，如2012-02-05~2012-03-06的日期差数

## 28.   一个衣柜中放了许多杂乱的衬衫，如果让你去整理一下，使得更容易找到你想要的衣服；你会怎么做？请写出你的做法和思路？

## 29.   如何优化网页加载速度？

   1.减少css，js文件数量及大小(减少重复性代码，代码重复利用)，压缩CSS和Js代码

   2.图片的大小

   3.把css样式表放置顶部，把js放置页面底部   

   4.减少http请求数

   5.使用外部 Js 和 CSS

## 30.   工作流程，你怎么来实现页面设计图，你认为前端应该如何高质量完成工作?

熟悉相关设计规范，自己总结的一些经验

## 31.   介绍项目经验、合作开发、独立开发。

团队协作，个人能力。实践经验

## 32.   开发过程中遇到困难，如何解决。

考察解决问题的能力

## 33.   对前端界面工程师这个职位是怎么样理解的？它的前景会怎么样？

    前端是最贴近用户的程序员，比后端、数据库、产品经理、运营、安全都近。
    
    1、实现界面交互
    
    2、提升用户体验
    
    3、有了Node.js，前端可以实现服务端的一些事情

前端是最贴近用户的程序员，前端的能力就是能让产品从 90分进化到 100 分，甚至更好， 

参与项目，快速高质量完成实现效果图，精确到1px；

与团队成员，UI设计，产品经理的沟通； 

做好的页面结构，页面重构和用户体验； 

处理hack，兼容、写出优美的代码格式； 

针对服务器的优化、拥抱最新前端技术。

其它相关的加分项：

## 1. 都使用和了解过哪些编辑器?都使用和了解过哪些日常工具?

## 2. 都知道有哪些浏览器内核?开发过的项目都兼容哪些浏览器?

## 3. 瀑布流布局或者流式布局是否有了解

## 4. HTML5都有哪些新的API?

## 5. 都用过什么代码调试工具?

## 6. 是否有接触过或者了解过重构。

7.你遇到过比较难的技术问题是？你是如何解决的？