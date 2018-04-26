Markdown 测试文档
=======
* [概述](#overview)
	* [兼容HTML](#HTML)
	* [特殊字符自动转换](#autoescape)
* [区块元素](#block)
	* [段落和换行](#p)
	* [标题](#header)
	* [区块引用](#blockquote)
	* [列表](#list)
	* [代码分块](#precode)
	* [分隔线](#hr)
* [区段元素](#span)
	* [链接](#link)
	* [强调](#em)
	* [代码](#code)
	* [图片](#img)
* [其他](#misc)
	* [反斜杠](#backslash)
	* [自动链接](#autolink)



***
<h2 id = "overview">概述</h2>
这份文档派生(fork)于[繁体中文版](http://markdown.tw/)，在此基础上进行了繁体转简体工作，并进行了适当的润色。此文档用 Markdown 语法编写，你可以到这里[查看它的源文件][src1]。「繁体中文版的原始文件可以[查看这里][src] 。」--By @[riku][t]
[t]: http://twitter.com/riku
[src]: https://github.com/othree/markdown-syntax-zhtw/blob/master/syntax.md
<h3 id = "HTML">兼容HTML</h3>
<table>
   <tr>
      <td>姓名</td>
      <td>性别</td>
      <td>生日</td>
   </tr>
</table>
<h3 id = "autoescape">特殊字符自动转换</h3>
&lt;
&amp;
&copy;
AT&T
<h2 id = "block">区块元素</h2>
<h3 id = "p">段落和换行</h3>
<br />换行  
换行
<h3 id = "header">标题</h3>
标题
==============
标题
-------------
# 标题
## 标题
<h3 id = "blockquote">区块引用</h3>
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> >consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> ###标题
<h3 id = "list">列表</h3>
*   Red
+   Green
-   Blue
3.  Red
2.  Green
1.  Blue
<ol>
<li>Bird</li>
<li>McHale</li>
<li>Parish</li>
</ol>
3\.  Red
<h3 id = "precode">代码区块</h3>
<pre><code>tell application "Foo"
    &amp;beep
end tell
</code></pre>
	tell application "Foo"
		beep 
	&lt;/div&gt;
	end tell
