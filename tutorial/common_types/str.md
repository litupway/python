# 字符串

<strong>字符串（String）</strong>是 Python 里最常见且最基础的类型之一。

## f-string

<div class="msg msg-info">
    <div style="margin-right: 10px;">
        <img src="/python/assets/python/3.6.svg" width="45px">
    </div>
    <div style="flex: 1;">
        <strong>此特性只支持 Python 3.6+</strong><br/>
        Python 3.6 或低于请使用 format！
    </div>
</div>

**f-string**，正式名称**格式化字符串常量（Formatted String Literals）**，是 Python 3.6 发布为了替代 format 的语法。

### 语法

...

### 例子

<pre class="language-Python" data-lang="Python"><code class="lang-Python language-Python" tabindex="0">name <span class="key">=</span> <span class="str">"MBLC7"</span>

<span class="fun">print</span><span class="con">(</span><span class="key">f</span><span class="str">"我的名字是 </span><span class="spc">{</span>name<span class="spc">}</span><span class="str">！"</span><span class="con">)</span></code></pre>

**输出**

``` 控制台
我的名字是 MBLC7！
```

<link rel="stylesheet" href="/python/parse.css"/>