# html基础
## 1.HTML基础
### 1.1 HTML标题
>标题是通过<h1>--<h6>标签来定义的
 ```
 <h1>标题</h1>
 ```
### 1.2 HTML段落
 >段落是通过<p><p>标签来定义的
 ```
 <p>这是一个段落</p>
 ```
### 1.3HTML链接
> 通过a标签来定义
```
<a href="url">链接</a>
```
### 1.4HTML图像
>通过img标签定义
```
<img src="/images/logo.png" />
```
## 2.HTML属性
>属性可以在元素中添加附加信息，一般用于描述标签，name="value"。 大多数html的适用属性 class id style title。
## 3.HTML文本格式化标签
```
 <b>	定义粗体文本
 <em>	定义着重文字
 <i>	定义斜体字
 <small>	定义小号字
 <strong>	定义加重语气
 <sub>	定义下标字
 <sup>	定义上标字
 <ins>	定义插入字
 <del>	定义删除字
```
## 4.HTML链接
### 4.1 html链接 target属性
> target属性规定链接在何处被打开
```
<a href="http://www.baidu.com/" target="_blank">访问百度</a>
```
### 4.2 html id属性
> idd属性可用于创建在一个HTML文档书签标记,书签是不以任何特殊的方式显示，在HTML文档中是不显示的，所以对于读者来说是隐藏的
## 5.HTML头部
### 5.1 title标签
>title 定义了不同文档的标题，显示在搜索引擎结果页面的标题
### 5.2 base标签
> base 标签描述了基本的链接地址/链接目标，该标签作为HTML文档中所有的链接标签的默认链接
```
<head>
<base href="http://www.baidu.com/" target="_blank">
</head>
```
### 5.3 link标签
>link标签定义了文档与外部资源的关系
```
<link rel="stylesheet" type="text/css" href="mystyle.css">
```
### 5.4 style标签
>style标签 定义了html文档的样式文件进用地址 也可以直接添加样式渲染文档
```
<head>
<style type="text/css">
body {background-color:yellow}
p {color:blue}
</style>
</head>
```
### 5.5 meta标签
> 描述一些基本的元数据，会被解析但不在页面中显示
```
<meta name="keywords" content="HTML, CSS, XML, XHTML, JavaScript">
<meta name="description" content="描述内容">
<meta name="author" content="author">
<meta http-equiv="refresh" content="30">

```
### 5.6 script标签
> 加载脚本文件，在javascript章节详细描述
## 6.HTML CSS
### 6.1 内联样式
```
<p style="color:blue;margin-left:20px;">This is a paragraph.</p>
```
### 6.2 内部样式表
```
<head>
<style type="text/css">
body {background-color:yellow;}
p {color:blue;}
</style>
</head>
```
### 6.3 外部引用
```
<head>
<link rel="stylesheet" type="text/css" href="style.css">
</head>
```
## 7.HTML图像
> alt属性:没有图片地址时的描述信息 title属性图片的描述信息
## 8.HTML表格
>tr定义表格的行  td定义表格的列 th定义表格的表头  border属性定义表格的边框
```
<table border="1">
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr
    <tr>
        <td>row 1, cell 1</td>
        <td>row 1, cell 2</td>
    </tr>
    <tr>
        <td>row 2, cell 1</td>
        <td>row 2, cell 2</td>
    </tr>
</table>
```
> caption  colgroup col theader tbody tfoot
## 9.HTML列表
### 9.1 有序列表
```
<ol>
<li>Coffee</li>
<li>Milk</li>
</ol>
```
### 9.2 无序列表
```
<ul>
<li>Coffee</li>
<li>Milk</li>
</ul>
```
### 9.3 自定义列表
```
<dl>
<dt>Coffee</dt>
<dd>- black hot drink</dd>
<dt>Milk</dt>
<dd>- white cold drink</dd>
</dl>
```
## 10.HTML区块
### 10.1块元素
> 块级元素大多为结构性标记 例如：h1-h6 p div ul ol dl table form ...
```
  1.总是从新的一行开始
  2.高度、宽度都是可控的
  3.宽度没有设置时，默认为100%
  4.块级元素中可以包含块级元素和行内元素
```

### 10.2内联元素
> 内联元素大多为描述性标记 例如: span a br b img input ...
```
  1.和其他元素都在一行
  2.高度、宽度以及内边距都是不可控的
  3.宽高就是内容的高度，不可以改变
  4.行内元素只能行内元素，不能包含块级元素
```
### 11.HTML表单 form
> 表单标签： form input textarea label fieldset legend select optgroup option button html5新增:datalist keygen output
### 12.HTML框架 iframe
>通过使用框架，你可以在同一个浏览器窗口中显示不止一个页面。
```
<iframe src="demo_iframe.htm" name="iframe_a"></iframe>
<p><a href="http://www.baidu.com" target="iframe_a">baidu</a></p>
```

