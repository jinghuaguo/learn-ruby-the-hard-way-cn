习题0：安装
=====================

这道习题没有变成内容。它将帮助你安装并运行Ruby。
你应该尽可能的按照说明操作。

这部分教学假设你将使用Ruby 1.9.2

你的系统可能已经安装好Ruby了。打开 Terminal 并执行：

.. code-block:: console

    $ ruby -v
    ruby 1.9.2

如果你还没有安装Ruby，无论你是用的是什么操作系统，我强烈建议你使用
`Ruby Version Manager(RVM) <https://rvm.beginrescueend.com/>`_ 来安装。

Mac OS X
-------

做下列任务来完成习题：

1.  用浏览器打开
    `http://learnpythonthehardway.org/exercise0.html <http://learnpythonthehardway.org/exercise0.html>`_ 
    下载并安装 ``gedit`` 文本编辑器。
2.  把 ``gedit`` 放到Dock上，这样你就可以方便的使用它了。

    1. 打开gedit，我们要先改掉一些愚蠢的设置
    2. 从 ``gedit menu`` 中打开 ``Preferences`` ，选择 ``Editor`` 标签
    3. 将 ``Tab width`` 改为2.
    4. 选择 (确认有勾选到该选项)
       ``Insert spaces instead of tabs``.
    5. 打开 ``Automatic indentation`` 选项
    6. 转到 ``View`` 页面并打开 ``Display line numbers`` 选项

3.  找到系统中的 "命令行终端(Terminal)" 程序。到处找找，你会找到的。
4.  把 Terminal 也放到 Dock 里面。
5.  运行 Terminal 程序，这个程序看上去不怎么地。
6.  在 Terminal 程序里边运行 ``irb`` (Ruby的互交式界面). 
    在 Terminal 中运行程序的方法是输入程序的名字再敲一下回车。

    1. 如果你运行 ``irb`` 但系统提示不存在该程序( ``irb`` 默认不会安装
       ..). 用
       `Ruby Version Manager(RVM) <https://rvm.beginrescueend.com/>`_
       来安装它

7.  敲击 CTRL-D (``^D``) 退出 ``irb``.
8.  这样你就应该退回到敲 ``irb`` 前的提示界面了。
    如果没有的话自己研究一下为什么。
9.  学着使用 Terminal 创建一个目录，你可以百度一下。
10. 学着使用 Terminal 进入一个目录，同样你可以去问度娘。
11. 使用你的编辑器在你进入的目录下建立一个文件。你将建立一个文件。
    使用 ``Save`` 或者 ``Save As...`` 选项，然后选择这个目录。
12. 使用键盘切换回到 Terminal 窗口，如果不知道怎样使用键盘切换，你一样可以去百度。
13. 回到 Terminal，看看你能不能使用命令看到你新建的文件，百度一下如何将文件夹中的内容列出来。

.. note::

    如果你在gedit上有问题，那很可能是因为使用非英式键盘造成的，
    我建议你使用Textwrangler，你可以在这里找到它：
    `http://www.barebones.com/products/textwrangler/ <http://www.barebones.com/products/textwrangler/>`_
    instead.

OSX: 你应该看到的
------------------------

以下是我在自己电脑的 Terminal 中执行上述练习时看到的内容。
和你做的结果会有一些不同，所以看看你能不能找出两者不同点来。

.. code-block:: console

    Last login: Sat Apr 24 00:56:54 on ttys001
    ~ $ irb
    ruby-1.9.2-p180 :001 >
    ruby-1.9.2-p180 :002 > ^D
    ~ $ mkdir mystuff
    ~ $ cd mystuff
    mystuff $ ls
    # ... Use Gedit here to edit test.txt....
    mystuff $ ls
    test.txt
    mystuff $

Windows
-------

.. note::

    由zhmark贡献


1.  用浏览器打开
    `http://learnpythonthehardway.org/exercise0.html <http://learnpythonthehardway.org/exercise0.html>`_
    下载并安装``gedit``文本编辑器。你不需要管理员权限也能顺利安装。
2.  把 ``gedit`` 放到桌面或者快速启动栏，这样你就可以方便地访问到该程序了。这两条在安装选项中可以看到。

    1. 打开gedit，我们要先改掉一些愚蠢的设置
    2. 从 ``gedit menu`` 中打开 ``Preferences`` ，选择 ``Editor`` 标签
    3. 将 ``Tab width`` 改为2.
    4. 选择 (确认有勾选到该选项)
       ``Insert spaces instead of tabs``.
    5. 打开 ``Automatic indentation`` 选项
    6. 转到 ``View`` 页面并打开 ``Display line numbers`` 选项
    
3.  找到 ``Terminal`` 程序。它的名字是 ``Command Prompt`` ，或者你可以直接运行 ``cmd`` 。 
4.  为它创建一个快捷方式，放到桌面或者快速启动栏中以方便使用。
5.  运行 Terminal 程序，这个程序看上去不怎么地。
6.  在 Terminal 程序里边运行 ``irb`` (Ruby的互交式界面). 
    在 Terminal 中运行程序的方法是输入程序的名字再敲一下回车。

    1. 如果你运行 ``irb`` 但系统提示不存在该程序( ``irb`` 默认不会安装
       ..). 用
       `Ruby Version Manager(RVM) <https://rvm.beginrescueend.com/>`_
       来安装它

7.  敲击 CTRL-Z (``^Z``) 退出 ``irb``.
8.  这样你就应该退回到敲 ``irb`` 前的提示界面了。
    如果没有的话自己研究一下为什么。
9.  学着使用 Terminal 创建一个目录，你可以百度一下。
10. 学着使用 Terminal 进入一个目录，同样你可以去问度娘。
11. 使用你的编辑器在你进入的目录下建立一个文件。你将建立一个文件。
    使用 ``Save`` 或者 ``Save As...`` 选项，然后选择这个目录。
12. 使用键盘切换回到 Terminal 窗口，如果不知道怎样使用键盘切换，你一样可以去百度。
13. 回到 Terminal，看看你能不能使用命令看到你新建的文件，百度一下如何将文件夹中的内容列出来。

.. warning::

    在Windows上使用Ruby就是个悲剧。有时候在一台电脑上装ruby没事，
    在另一台电脑上就会漏掉一堆重要的功能。
    如果你遇到问题了，你可以访问：
    `http://rubyinstaller.org/ <http://rubyinstaller.org/>`_

Windows: 你应该看到的
----------------------------

.. code-block:: console

    C:\Documents and Settings\you>irb
    ruby-1.9.2-p180 :001 >
    ruby-1.9.2-p180 :001 > ^Z

    C:\Documents and Settings\you>mkdir mystuff

    C:\Documents and Settings\you>cd mystuff

    ... Here you would use gedit to make test.txt in mystuff ...

    C:\Documents and Settings\you\mystuff>
       <bunch of unimportant errors if you istalled it as non-admin - ignore them - hit Enter>
    C:\Documents and Settings\you\mystuff>dir
     Volume in drive C is
     Volume Serial Number is 085C-7E02

     Directory of C:\Documents and Settings\you\mystuff

    04.05.2010  23:32    <DIR>          .
    04.05.2010  23:32    <DIR>          ..
    04.05.2010  23:32                 6 test.txt
                   1 File(s)              6 bytes
                   2 Dir(s)  14 804 623 360 bytes free

    C:\Documents and Settings\you\mystuff>

你看到的命令行信息，Ruby 信息，以及其它一些东西可能会非常不一样，
不过应该大致不差。你可以把你找到的错误告诉我们，我们会修正过来。

Linux
-----

Linux 系统可谓五花八门，安装软件的方式也各有不同。
我们假设作为 Linux 用户的你已经知道如何安装软件包了，以下是给你的操作说明：

1.  用浏览器打开
    `http://learnpythonthehardway.org/exercise0.html <http://learnpythonthehardway.org/exercise0.html>`_
    下载并安装 ``gedit``文本编辑器。（Ubuntu中默认的文本编辑器即为gedit --译注）
2.  把 ``gedit`` (也就是你的编辑器) 放到窗口管理器显见的位置，以方便日后使用

    1. 打开gedit，我们要先改掉一些愚蠢的设置
    2. 从 ``gedit menu`` 中打开 ``Preferences`` ，选择 ``Editor`` 标签
    3. 将 ``Tab width`` 改为2.
    4. 选择 (确认有勾选到该选项)
       ``Insert spaces instead of tabs``.
    5. 打开 ``Automatic indentation`` 选项
    6. 转到 ``View`` 页面并打开 ``Display line numbers`` 选项

3.  找到 "Terminal" 程序。它可能叫GNOME Terminal,Konsole, 或者 xterm.
4.  把 Terminal 也放到 Dock 里面。（似乎是原作有误，多数Linux发行版没有预装Dock程序，同样扔到窗口管理器就好 --译注）
5.  运行 Terminal 程序，这个程序看上去不怎么地。
6.  在 Terminal 程序里边运行 ``irb`` (Ruby的互交式界面). 
    在 Terminal 中运行程序的方法是输入程序的名字再敲一下回车。

    1. 如果你运行 ``irb`` 但系统提示不存在该程序( ``irb`` 默认不会安装
       ..). 用
       `Ruby Version Manager(RVM) <https://rvm.beginrescueend.com/>`_
       来安装它

7.  敲击 CTRL-D (``^D``) 退出 ``irb``.
8.  这样你就应该退回到敲 ``irb`` 前的提示界面了。
    如果没有的话自己研究一下为什么。
9.  学着使用 Terminal 创建一个目录，你可以百度一下。
10. 学着使用 Terminal 进入一个目录，同样你可以去问度娘。
11. 使用你的编辑器在你进入的目录下建立一个文件。你将建立一个文件。
    使用 ``Save`` 或者 ``Save As...`` 选项，然后选择这个目录。
12. 使用键盘切换回到 Terminal 窗口，如果不知道怎样使用键盘切换，你一样可以去百度。
13. 回到 Terminal，看看你能不能使用命令看到你新建的文件，百度一下如何将文件夹中的内容列出来。

Linux: 你应该看到的
--------------------------

.. code-block:: console

    $ irb
    ruby-1.9.2-p180 :001 > 
    ruby-1.9.2-p180 :002 > ^D
    $ mkdir mystuff
    $ cd mystuff
    # ... Use gedit here to edit test.txt ...
    $ ls
    test.txt
    $

你看到的命令行信息，Ruby 信息，以及其它一些东西可能会非常不一样。不过应该大致不差就是了。

给新手的告诫
----------------------

你已经完成了这节练习。取决于你对计算机的熟练程度，这节练习可能对你来说挺难的。
如果你觉得压力山大，多花点时间学习一下，努力克服一下困难。
因为如果你不会这些基础操作的话，编程对你来说将会更难学习。

如果有个程序员让你用 ``vim`` 或者 ``emacs``，你应该拒绝他们。
当你成为一个更好的程序员的时候再去试着使用这些编辑器吧。
现在你所需要的编辑器只要能打字就可以了。
我们使用 ``gedit`` 因为它便于使用而且跨平台。
就连专业程序员也会使用 ``gedit`` ，所以对于初学来说它已经够了。

总有一天你会听到有程序员建议你用Mac OS X或者Linux。
如果这个程序员喜欢美丽的字体，他会建议你去买一台苹果电脑。
如果他们喜欢操控系统而且有一个大胡子，他们会让你去装Linux.
再次声明，你手上只要有一台能用的电脑就行了。
你所需要的只有 ``gedit`` ，终端（Terminal），以及Ruby。

最后要说的是这节练习的准备工作的目的，也就是让你可以在以后的练习中顺利地做到下面的这些事情：

1. 使用 ``gedit`` 编写代码。
2. 运行你写的习题。
3. 修改错误的习题。
4. 重复上述步骤。

其他的事情只会让你更困惑，所以还是坚持按计划进行吧。
