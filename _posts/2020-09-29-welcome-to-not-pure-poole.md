---
layout: post
title: Welcome to 我的博客
date: 2021-05-29 08:08 +0800
last_modified_at: 2021-06-01 01:08:25 +0800
tags: [jekyll theme, 学习, 感谢]
toc:  true
---
欢迎来到 **我的博客**! 这是一个简单，美丽而又荒诞不羁的博客，你可以尽情提建议啦.
{: .message }

首先欢迎各位光临我的博客啦，（此处应有掌声：呱唧呱唧！）那么什么是博客呢？博客，仅音译，英文名为Blogger，为Web Log的混成词。它的正式名称为网络日记；又音译为部落格或部落阁等，是使用特定的软件，在网络上出版、发表和张贴个人文章的人，或者是一种通常由个人管理、不定期张贴新的文章的网站。

 心中装满快乐，人生才会阳光；心里装满感恩，人生才会祥和；心里装满友善，人生才会充实；心里装满爱意，人生才会温暖；心里种满希望，人生才会如意；心里装满猜疑，人生就会充满不安；心里装满怨恨，人生就充满动荡；心里装满不宵，人生就会孤独；心里装满自私，人生就会充满陷阱。

> 人总是在经历了一些事，才会达到一定的高度。有些事，没有切身经历，就不能体会那种感受。人说旁观者清，其实当事者才清。有些事，要靠自己才能捋得清，走得出。人在走出一件事后，也就经历了一次重生。

希望大家幸福安康又快乐，感谢大家捧场啦，祝您玩的愉快！.

## Inline HTML elements

HTML 定义了一长串可用的内联标签，完整的列表可以在[Mozilla Developer Network]上找到(https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

[comment]: <> (- **To bold text**, use `<strong>`.)

[comment]: <> (- *To italicize text*, use `<em>`.)

[comment]: <> (- <mark>To highlight</mark>, use `<mark>`.)

[comment]: <> (- Abbreviations, like <abbr title="HyperText Markup Langage">HTML</abbr> should use `<abbr>`, with an optional `title` attribute for the full phrase.)

[comment]: <> (- Citations, like <cite>&mdash; Mark Otto</cite>, should use `<cite>`.)

[comment]: <> (- <del>Deleted</del> text should use `<del>` and <ins>inserted</ins> text should use `<ins>`.)

[comment]: <> (- Superscript <sup>text</sup> uses `<sup>` and subscript <sub>text</sub> uses `<sub>`.)

大多数这些元素是由浏览器设计的，我们几乎没有修改。

## Footnotes

脚注作为 Markdown 语法的一部分受支持。 这是一个在行动。 单击此数字[^fn-sample_footnote] 将引导您到脚注。语法如下：

{% highlight text %}
点击这个数字[^fn-sample_footnote]
{% endhighlight %}

每个脚注都需要 `^fn-` 前缀和一个唯一的 ID，以供脚注内容引用。 该列表的语法如下所示：

{% highlight text %}
[^fn-sample_footnote]: ok啦！现在点击这里回去了
{% endhighlight %}

您可以将脚注内容放在您喜欢的任何位置。 Markdown 解析器应该正确地将它放在帖子的底部。
## Heading

头部部分，暂时我还不知道有啥作用哈，慢慢来学习

### Code

内联代码可用于 `<code>` 元素。 Rouge 支持多行代码片段。 需要时，较长的行将自动水平滚动。 您还可以使用代码围栏（三重反引号）来呈现代码。

{% highlight js %}
// 示例可以直接在您的 JavaScript 控制台中运行

// 创建一个函数，它接受两个参数并返回这些参数的总和
var adder = new Function("a", "b", "return a + b");

// 调用函数
加法器(2, 6);
// > 8
{% endhighlight %}

您还可以选择显示带有行号的代码片段。 将 `linenos` 添加到 Rouge 标签。

{% highlight js linenos %}
// 示例可以直接在你的 JavaScript 控制台中运行

// 创建一个函数，它接受两个参数并返回这些参数的总和
var adder = new Function("a", "b", "return a + b");

// 调用函数
加法器(2, 6);
// > 8
{% endhighlight %}

仍然不知道这个语法

### Lists

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.

- Praesent commodo cursus magna, vel scelerisque nisl consectetur et.
- Donec id elit non mi porta gravida at eget metus.
- Nulla vitae elit libero, a pharetra augue.

Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae elit libero, a pharetra augue.

1. Vestibulum id ligula porta felis euismod semper.
2. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
3. Maecenas sed diam eget risus varius blandit sit amet non magna.

Cras mattis consectetur purus sit amet fermentum. Sed posuere consectetur est at lobortis.

<dl>
  <dt>HyperText Markup Language (HTML)</dt>
  <dd>The language used to describe and define the content of a Web page</dd>

  <dt>Cascading Style Sheets (CSS)</dt>
  <dd>Used to describe the appearance of Web content</dd>

  <dt>JavaScript (JS)</dt>
  <dd>The programming language used to build advanced Web sites and applications</dd>
</dl>

Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo.

### Images

Quisque consequat sapien eget quam rhoncus, sit amet laoreet diam tempus. Aliquam aliquam metus erat, a pulvinar turpis suscipit at.

![placeholder](http://placehold.it/800x400 "Large example image")
![placeholder](http://placehold.it/400x200 "Medium example image")
![placeholder](http://placehold.it/200x200 "Small example image")

Align to the center by adding `class="align-center"`:

![placeholder](http://placehold.it/400x200 "Medium example image"){: .align-center}

### Tables

Aenean lacinia bibendum nulla sed consectetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Upvotes</th>
      <th>Downvotes</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <td>Totals</td>
      <td>21</td>
      <td>23</td>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>10</td>
      <td>11</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Charlie</td>
      <td>7</td>
      <td>9</td>
    </tr>
  </tbody>
</table>

Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.

-----

Want to see something else added? <a href="https://github.com/vszhub/not-pure-poole/issues/new">Open an issue.</a>

[^fn-sample_footnote]: 你又可以点击这里回去了.
