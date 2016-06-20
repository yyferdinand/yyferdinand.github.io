---
layout:     post
title:      "入职学习总结"
subtitle:   "写这篇总结最初的目的是老师安排我整理一下自己的入职学习经历，以便给以后新来的同事一些指南。"
date:       2016-01-06 15:27:00 
author:     "Fanxmistic"
header-img: "img/post/learn_for_freshman.jpg"
tags:
    - React
    - Sublime
    - 百度外卖
---
<div id='preview-contents' class='note-content'>
                        <div id="wmd-preview" class="preview-content"></div>
                    <div id="wmd-preview-section-64503" class="wmd-preview-section preview-content">

</div><div id="wmd-preview-section-64689" class="wmd-preview-section preview-content">

</div><div id="wmd-preview-section-64468" class="wmd-preview-section preview-content">

<h4 id="零前言">零、前言</h4>

<p>写这篇总结最初的目的是老师安排我整理一下自己的入职学习经历，以便给以后新来的同事一些指南。</p>

<p>其实，指南也算不上，因为我本身才疏学浅，还存在很多知识点的理解偏差，这篇总结出现一些错误肯定在所难免。至多给一点儿参考性的作用就已足够，更多的需要自己的思考与多问导师和身边的同事。</p>

<p>同时，这篇文章我也会同步在自己的博客当中，方便在线查看，这是 <a href="http://fanxmistic.github.io/2016/01/06/learning-for-freshman/" target="_blank">文章地址</a> 。</p>

</div><div id="wmd-preview-section-64469" class="wmd-preview-section preview-content">

<h4 id="一网站">一、网站</h4>

<p>这些网站都是我平时没事儿逛逛的，很多网站在移动端也有相应的 App，看到一些好文章就保存在自己的 <code>Pocket</code> 里面。逛主要是想给自己起到一个耳濡目染的作用。</p>

<ul><li><a href="https://www.zhihu.com" target="_blank">知乎</a></li>
<li><a href="http://segmentfault.com" target="_blank">Segmentfault</a></li>
<li><a href="http://toutiao.io/explore" target="_blank">开发者头条</a></li>
<li><a href="http://gold.xitu.io/#/" target="_blank">稀土掘金</a></li>
<li><a href="http://www.awwwards.com" target="_blank">AWWWARDS</a></li>
<li><a href="https://news.ycombinator.com" target="_blank">Hacker News</a></li>
<li><a href="http://stackoverflow.com" target="_blank">Stack Overflow</a></li>
<li><a href="http://www.ruanyifeng.com/blog/" target="_blank">阮一峰的博客</a></li>
<li><a href="http://blog.evanyou.me" target="_blank">尤小右的博客</a></li>
<li><a href="http://huangxuan.me" target="_blank">黄玄的博客</a></li>
<li><a href="http://glexe.com/?from=inf&amp;wvr=5&amp;loc=infblog#/" target="_blank">Eisneim的博客</a></li>
</ul>

</div><div id="wmd-preview-section-64470" class="wmd-preview-section preview-content">

<h4 id="二sublime">二、Sublime</h4>

<p>由于我自身用的是 MacBook Pro,一些快捷键会与 Win 不同，很多情况，Mac 上的 <code>Command</code>键对应 Win 上的 <code>Ctrl</code> 键。</p>

</div><div id="wmd-preview-section-64471" class="wmd-preview-section preview-content">

<h5 id="21-快捷键">2.1 、快捷键</h5>

<pre class="prettyprint hljs-light"><code class="hljs asciidoc"><span class="hljs-comment line-number">1.</span><span class="hljs-bullet">* </span>⌘    Command <br><span class="hljs-comment line-number">2.</span><span class="hljs-bullet">* </span>⌃    Control <br><span class="hljs-comment line-number">3.</span><span class="hljs-bullet">* </span>⌥    Option <br><span class="hljs-comment line-number">4.</span><span class="hljs-bullet">* </span>⇧    Shift <br></code></pre>

<p>＃ 编辑 Edit</p>

<ul><li><code>⌘[</code> 向左缩进 | Left indent</li>
<li><code>⌘]</code>  向右缩进 | Right Indent</li>
<li><code>⌘⌃↑</code> 与上一行互换 | Swap line up</li>
<li><code>⌘⌃↓</code>与下一￼行互换￼ | Swap line down</li>
<li><code>⌘J</code> 拼接行（css格式化时挺有用） | join lines</li>
<li><code>⌘←</code> 去往行的开头 | Beginning of line</li>
<li><code>⌘→</code> 去往行末尾 | End of line</li>
<li><code>⌘⌥/</code> 块注释 | Toggle comment block</li>
<li><code>⌃K</code> 从光标开始的地方删除到行尾 | Delete to end</li>
<li><code>⌃⇧K</code> 删除一整行 | delete line</li>
<li><code>⌃D</code> 取中删除</li>
</ul>

<p>＃ 光标选中 Selection</p>

<ul><li><code>⌘D</code> 选中相同的词 | Expand selection to words</li>
<li><code>⌃⌘G</code> 多重文本光标选中 | Expand all selection to words</li>
<li><code>⌘L</code> 选中一行 | Expand selection to line</li>
<li><code>⌥+拖动鼠标</code> 多重光标选中</li>
<li><code>⌘⇧J</code> 已缩进层级为依据，一层层向外选中|Expand selection to indentation</li>
</ul>

<p>＃ 跳转／定位 Go to</p>

<ul><li><code>⌘P</code> 跳转文件 | Go to anything</li>
<li><code>⌘R</code> 定位文件中的方法 | Go to symbol</li>
</ul>

<p>＃ 通用 General</p>

<ul><li><code>⌘⇧P</code>  打开命令行| Command prompt</li>
<li><code>⌘KB</code> 隐藏/打开 侧边栏| Toggle side bar</li>
</ul>

<p>＃ 标签栏</p>

<ul><li><code>⌘⇧t</code>  打开最后一次关闭的文件|Open last closed tab</li>
<li><code>^Tab</code>  循环遍历tab|Cycle up through tabs</li>
<li><code>^⇧Tab</code>  反方向循环遍历tab|Cycle down through tabs</li>
</ul>

</div><div id="wmd-preview-section-64472" class="wmd-preview-section preview-content">

<h5 id="22插件">2.2、插件</h5>

<p>推荐一些自己常用的 Sublime 插件，如何安装插件和插件介绍不再累赘，只是简单的罗列。</p>

<ul><li><code>SideBarEnhancements</code></li>
<li><code>Markdown Preview\Markdown Editing</code></li>
<li><code>Emmet</code></li>
<li><code>HTML-CSS-JS Prettify</code></li>
<li><code>SublimeCodeIntel</code></li>
<li><code>JSHint</code></li>
<li><code>SublimeLinter</code></li>
</ul>

</div><div id="wmd-preview-section-64880" class="wmd-preview-section preview-content">

<h4 id="三other">三、Other</h4>

<blockquote>
  <p>未完待续 ……</p>
</blockquote></div><div id="wmd-preview-section-footnotes" class="preview-content"></div></div>