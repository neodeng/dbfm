Douban-FM Box
=============
<pre>
d8888b    d88b   db    db d8888b   .d8b.  d8b   db      d88888b .88b  d88.
88   8D .8P  Y8. 88    88 88   8D d8   8b 888o  88      88      88 YbdP 88
88   88 88    88 88    88 88oooY  88ooo88 88V8o 88      88ooo   88  88  88
88   88 88    88 88    88 88ooob  88ooo88 88 V8o88      88ooo   88  88  88
88   8D '8b  d8' 88b  d88 88   8D 88   88 88  V888      88      88  88  88
Y8888D    Y88P    Y8888P  Y8888P  YP   YP VP   V8P      YP      YP  YP  YP
</pre>

简洁的豆瓣电台Linux版，基于python编写

###功能特性

1. 模拟豆瓣FM，支持热门兆赫的选择
2. 支持快捷键切换兆赫、切换歌曲
3. 可以随意切换全屏模式和悬浮模式
4. ubuntu支持发送通知到桌面

###环境支持

1. Linux
2. Python2.7+

###安装

运行以下命令进行安装，由于依赖[mpg123](http://www.mpg123.de/)播放器，若系统未安装则会自动进行安装：

    $ sudo ./install.sh

###使用方法

在终端输入：

    $ dbfm

###快捷键

<table>
    <tr><td>####按键####</td><td>####说明####</td></tr>
    <tr><td>k</td><td>上移</td></tr>
    <tr><td>j</td><td>下移</td></tr>
    <tr><td>h</td><td>上一兆赫</td></tr>
    <tr><td>l</td><td>下一兆赫</td></tr>
    <tr><td>[</td><td>上一首</td></tr>
    <tr><td>]</td><td>下一首</td></tr>
    <tr><td>space</td><td>播放/暂停</td></tr>
    <tr><td>p</td><td>桌面/悬浮</td></tr>
    <tr><td>m</td><td>帮助</td></tr>
    <tr><td>q</td><td>退出</td></tr>
</table>

### The MIT License (MIT)

CopyRight (c) 2015 nerodeng  &lt;<a href="mailto:dyq9109@163.com">dyq9109@163.com</a>&gt;

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

