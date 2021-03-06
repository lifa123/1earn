# Markdown 语法学习

<p align="center">
    <img src="../../../../assets/img/logo/markdown.svg" width="15%">
</p>


---

`注:本文档所有内容来自以下来源,非本人原创,特此声明`

`注:本文档所有内容来自以下来源,非本人原创,特此声明`

`注:本文档所有内容来自以下来源,非本人原创,特此声明`

`注:本文档所有内容来自以下来源,非本人原创,特此声明`

- [Editor.md](https://github.com/pandao/editor.md/blob/master/examples/test.md)
-  [https://guides.github.com/features/mastering-markdown](https://guides.github.com/features/mastering-markdown)
-  [https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/)
- [Markdown 语法说明 (简体中文版)](https://www.appinn.com/markdown/)

---

![image](https://user-images.githubusercontent.com/1908863/28227953-eb6eefa4-68a1-11e7-8769-96ea83facf3b.png)

列表
- Bulleted
- List
- **Markdown 代码块**
- **Python 代码块**
- **Ruby 代码块**
+ s
+ s
* a
* a

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item


正如 Kanye West 所说:
> We're living the future so
> the present is our past.
>> s
>>> a
>>>> b
>>>>> f

我觉得你应该在这里使用`<addr>` 才对.

&copy;

<br/>
<h1>what the fuck</h1>
<h2>this is html</h2>

this is H1
===

this is H2
---

---

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium
The HTML specification
is maintained by the W3C.

H~2~O
30^th^
:smile:
:fa-car:

==marked==

### 下面是 Markdown 代码块
```markdown

标题
# 一级标题
## 二级标题
### 三级标题

1. Numbered
2. List

3. a
2. a

\*literal asterisks\*

加粗和斜体
**加粗**
*斜体*

代码块(去掉\)
\```
code
\```
```

---

**目录 (Table of Contents)**

[TOCM]

[TOC]

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
# Heading 1 link [Heading link](https://github.com/pandao/editor.md "Heading link")
## Heading 2 link [Heading link](https://github.com/pandao/editor.md "Heading link")
### Heading 3 link [Heading link](https://github.com/pandao/editor.md "Heading link")
#### Heading 4 link [Heading link](https://github.com/pandao/editor.md "Heading link") Heading link [Heading link](https://github.com/pandao/editor.md "Heading link")
##### Heading 5 link [Heading link](https://github.com/pandao/editor.md "Heading link")
###### Heading 6 link [Heading link](https://github.com/pandao/editor.md "Heading link")

#### 标题(用底线的形式)Heading (underline)

This is an H1
=============

This is an H2
-------------

### 字符效果和横线等

----

~~删除线~~ <s>删除线(开启识别HTML标签时)</s>
*斜体字*      _斜体字_
**粗体**  __粗体__
***粗斜体*** ___粗斜体___

上标:X<sup>2</sup>,下标:O<sub>2</sub>

**缩写(同HTML的abbr标签)**

> 即更长的单词或短语的缩写形式,前提是开启识别HTML标签时,已默认开启

The <abbr title="Hyper Text Markup Language">HTML</abbr> specification is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.

### 引用 Blockquote

> 引用文本 Blockquote

引用的行内混合 Blockquote

> 引用:如果想要插入空白换行`即<br />标签`,在插入处先键入两个以上的空格然后回车即可,[普通链接](http://localhost/).

### 锚点与链接 Links

[普通链接](http://localhost/)

[普通链接带标题](http://localhost/ "普通链接带标题")

直接链接:<https://github.com>

[锚点链接][anchor-id]

[anchor-id]: http://www.this-anchor-link.com/

GFM a-tail link @pandao

> @pandao

### 多语言代码高亮 Codes

#### 行内代码 Inline code

执行命令:`npm install marked`

#### 缩进风格

即缩进四个空格,也做为实现类似`<pre>`预格式化文本(Preformatted Text)的功能.

    <?php
        echo "Hello world!";
    ?>

预格式化文本:

    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |

#### JS代码　

```javascript
function test(){
    console.log("Hello world!");
}

(function(){
    var box = function(){
        return box.fn.init();
    };

    box.prototype = box.fn = {
        init : function(){
            console.log('box.init()');

            return this;
        },

        add : function(str){
            alert("add", str);

            return this;
        },

        remove : function(str){
            alert("remove", str);

            return this;
        }
    };

    box.fn.init.prototype = box.fn;

    window.box =box;
})();

var testBox = box();
testBox.add("jQuery").remove("jQuery");
```

#### HTML代码 HTML codes

```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <title>Hello world!</title>
    </head>
    <body>
        <h1>Hello world!</h1>
    </body>
</html>
```

<kbd>按键</kbd>

#### Git Diff 代码

```diff
function addTwoNumbers (num1, num2) {
-  return 1 + 2
+  return num1 + num2
}
```

---

### 图片 Images

Image:

![](https://pandao.github.io/editor.md/examples/images/4.jpg)

> Follow your heart.

![](https://pandao.github.io/editor.md/examples/images/8.jpg)

> 图为:厦门白城沙滩

图片加链接 (Image + Link):

[![](https://pandao.github.io/editor.md/examples/images/7.jpg)](https://pandao.github.io/editor.md/examples/images/7.jpg "李健首张专辑《似水流年》封面")

> 图为:李健首张专辑《似水流年》封面

----

### 列表 Lists

#### 无序列表(减号)Unordered Lists (-)

- 列表一
- 列表二
- 列表三

#### 无序列表(星号)Unordered Lists (*)

* 列表一
* 列表二
* 列表三

#### 无序列表(加号和嵌套)Unordered Lists (+)

+ 列表一
+ 列表二
    + 列表二-1
    + 列表二-2
    + 列表二-3
+ 列表三
    * 列表一
    * 列表二
    * 列表三

#### 有序列表 Ordered Lists (-)

1. 第一行
2. 第二行
3. 第三行

#### GFM task list

- [x] GFM task list 1
- [x] GFM task list 2
- [ ] GFM task list 3
    - [ ] GFM task list 3-1
    - [ ] GFM task list 3-2
    - [ ] GFM task list 3-3
- [ ] GFM task list 4
    - [ ] GFM task list 4-1
    - [ ] GFM task list 4-2

----

### 绘制表格 Tables

| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机      | $1600   |   5     |
| 手机        |   $12   |   12   |
| 管线        |    $1    |  234  |

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Function name | Description                    |
| ------------- | ------------------------------ |
| `help()`      | Display the help window.       |
| `destroy()`   | **Destroy your computer!**     |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

| Item      | Value |
| --------- | -----:|
| Computer  | $1600 |
| Phone     |   $12 |
| Pipe      |    $1 |

----

#### 特殊符号 HTML Entities Codes

&copy; &  &uml; &trade; &iexcl; &pound;
&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar; &macr; &laquo; &middot;

X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;

18&ordm;C  &quot;  &apos;

### Emoji表情 :smiley:

> Blockquotes :star:

#### GFM task lists & Emoji & fontAwesome icon emoji & editormd logo emoji :editormd-logo-5x:

- [x] :smiley: @mentions, :smiley: #refs, [links](), **formatting**, and <del>tags</del> supported :editormd-logo:;
- [x] list syntax required (any unordered or ordered list supported) :editormd-logo-3x:;
- [x] [ ] :smiley: this is a complete item :smiley:;
- [ ] []this is an incomplete item [test link](#) :fa-star: @pandao; 
- [ ] [ ]this is an incomplete item :fa-star: :fa-gear:;
    - [ ] :smiley: this is an incomplete item [test link](#) :fa-star: :fa-gear:;
    - [ ] :smiley: this is  :fa-star: :fa-gear: an incomplete item [test link](#);

#### 反斜杠 Escape

\*literal asterisks\*

### 科学公式 TeX(KaTeX)

$$E=mc^2$$

行内的公式$$E=mc^2$$行内的公式,行内的$$E=mc^2$$公式.

$$\(\sqrt{3x-1}+(1+x)^2\)$$

$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$

多行公式:

```math
\displaystyle
\left( \sum\_{k=1}^n a\_k b\_k \right)^2
\leq
\left( \sum\_{k=1}^n a\_k^2 \right)
\left( \sum\_{k=1}^n b\_k^2 \right)
```

```katex
\displaystyle
    \frac{1}{
        \Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{
        \frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {
        1+\frac{e^{-6\pi}}
        {1+\frac{e^{-8\pi}}
         {1+\cdots} }
        }
    }
```

```latex
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
```

### 绘制流程图 Flowchart

```flow
st=>start: 用户登陆
op=>operation: 登陆操作
cond=>condition: 登陆成功 Yes or No?
e=>end: 进入后台

st->op->cond
cond(yes)->e
cond(no)->op
```

### 绘制序列图 Sequence Diagram

```seq
Andrew->China: Says Hello
Note right of China: China thinks\nabout it
China-->Andrew: How are you?
Andrew->>China: I am good thanks!
```

---

# 表格方案

- https://tableconvert.com/

---

# 微信公众号方案

- https://github.com/cnych/markdown-weixin
- https://github.com/doocs/md

---

# 转pdf方案

- https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode
- https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced
    - 先从浏览器打开,在打印成pdf
- pandoc

---

# 转html方案

- https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced
    - 从浏览器打开,ctrl+s

---

# 转ppt方案

- https://github.com/hiroppy/fusuma

---

# 转word方案

可通过 Confluence 导出成word

创建笔记,直接将 markdown 代码复制进行即可排版,直接导出即可
