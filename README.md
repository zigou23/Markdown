**made by 麦米尔加弗德** 
<div align="right">
  语言:
  中文 /
  <a title="English" href="#">US</a>
</div>
<div align="center">
  <h1><a href="https://github.com/zigou23/Markdown" target="_blank">Markdown 语法</a></h1>
  <div align="center">
  </div>
  <p>Markdown</p>

[![commit-activity](https://img.shields.io/github/commit-activity/m/zigou23/Markdown)](https://github.com/zigou23/Markdown)
[![GPL3.0 License](https://img.shields.io/github/license/zigou23/Markdown?color=FF5531)](https://github.com/zigou23/Markdown/blob/master/LICENSE)
[![repo size](https://img.shields.io/github/repo-size/zigou23/Markdown?color=FFAC3B)](https://github.com/zigou23/Markdown/archive/refs/heads/main.zip)


[📘文档](https://github.com/zigou23/Markdown#1-%E5%9F%BA%E7%A1%80%E6%93%8D%E4%BD%9C) |
[:book:示例](https://github.com/zigou23/Markdown/blob/main/Example.md) |
[🤔报告问题](https://github.com/zigou23/Markdown/issues/new/)
</div>

# 1. 基础操作

## 1.1标题

```markdown
一级标题
=========   
二级标题
--------- 

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题
```

## 1.2 引用

```markdown
>  引用内容1
>  引用内容2
>> 引用内容3
```

## 1.3 斜体

```markdown
*斜体*
_斜体_
```

## 1.4 加粗

```markdown
**加粗**
__加粗__
***加粗斜体***
```

## 1.5 下划线

```markdown
<u>下划线</u>
```

## 1.6 删除线 

```markdown
~~删除线~~
```

## 1.7 分割线

```markdown
***
---
___
```

## 1.8 注脚

```markdown
Typora[^1]
[^1]:A markdown editor
```

## 1.9 上下标,高亮

```markdown
5<sup>2</sup>=25
H<sub>2</sub>OCO<sub>2</sub>
```

# 2. 代码

## 2.1 单行代码

```markdown
`String str1 = "hello`
```

## 2.3 注释,不会显示

```html
#html注释
<!-- 注释 -->
下面方法未知
#hack方法
[^_^]: # (我是注释，超级萌。)
*[·-·]:注释内容
*[^_^]:注释内容
*[@_@]:注释内容
```

# 3. 列表

## 3.1 无序列表

```markdown
* 无序列表1
+ 无序列表2
- 无序列表3
```



## 3.2 多行无序列表

```markdown
*         无序列表1
TAB *     无序列表2
TAB TAB * 无序列表3
```



## 3.3 有序列表

```markdown
1. 有序列表1
2. 有序列表2
3. 有序列表3
```



## 3.4 多行有序列表

```markdown
1. 多行有序列表1
2. 多行有序列表2
    1. 多行有序列表2-1
    2. 多行有序列表2-2
3. 多行有序列表3
    1. 多行有序列表3-1
    2. 多行有序列表3-2
```



## 3.5 任务列表

```markdown
- [ ] 任务1
- [x] 任务2(打勾的选项)
```



## 3.6 表格

```markdown
Ctrl + t
|姓名|性别|年龄|
|：---|：--：|：--：|
|张三|男|21|
|李四|女|23|
|王五|男|25|
```



# 4. 链接

## 4.1 图片

```markdown
![typora](图片的绝对地址)	#本地图片
![typora](图片的网络地址)	#网络图片
```



## 4.2 超链接

```markdown
样式1.
	[百度](https://www.baidu.com/)
样式2.
	[CSDN][CSDN网址]
	[CSDN网址]:https://www.csdn.net/
样式3.
	<https://www.csdn.net/>
```



## 4.3 框架

```markdown
<iframe src="链接"...参数...></iframe>
```



# 5. 符号的输入

## 5.1 普通符号

```markdown
\\
\`
\*
\_
\{\}
\[\]
\(\)
\#
\+
\-
\.
\!
```



## 5.2 特殊符号

```markdown
&copy;   版权
&reg;    注册商标
&trade;  商标
&nbsp;   空格
&amp;    和号
&quot;   引号
&apos;   撇号
&lt;     小于号
&gt;     大于号
&ne;     不等号
&le;     小于等于
&ge;     大于等于
&cent;   分
&pound;  磅
&euro;   欧元
&yen;    元
&sect;   节
&times;  乘号
&divide; 除号
&plusmn; 正负号
```



## 5.3 更多符号

[HTML特殊字符编码对照表](https://www.jb51.net/onlineread/htmlchar.htm)



## 5.4 表情符号

```markdown
#支持添加emoji表情，输入不同的符号码（两个冒号包围的字符）可以显示出不同的表情。
:smile:
```



# 6. 快捷键,仅针对typora

```markdown
Ctrl+1  	一阶标题    
Ctrl+2  	二阶标题    
Ctrl+3  	三阶标题    
Ctrl+4  	四阶标题    
Ctrl+5  	五阶标题    
Ctrl+6  	六阶标题    
Ctrl+B  	字体加粗(Blod)
Ctrl+I  	字体倾斜(Italic)
Ctrl+U  	下划线(Underline)
Ctrl+Z		撤销
Ctrl+T		创建表格(Table)				    
Ctrl+L  	选中某句话   
Ctrl+K  	创建超链接
Ctrl+D  	选中某个单词  
Ctrl+F  	搜索(Find)
Ctrl+H		搜索并替换
Ctrl+\		清楚样式
Ctrl+E  	选中相同格式的文字  
Ctrl+Home	 	返回Typora顶部	
Ctrl+End     	返回Typora底部
Alt+Shift+5 	删除线 
Ctrl+Shift+I    插入图片(Image)
Ctrl+Shift+M    公式块 
Ctrl+Shift+K	代码块
Ctrl+Shift+Q    引用(Quote)
```

