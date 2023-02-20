2023-02-19 15:57:54 Sun/07
--------------------------

迅雷极速版任务出错的解决办法
````````````````````````````
.. code-block:: rst

    使用迅雷极速版下载的提示“任务出错”，可以通过修改hosts文件的方法绕过迅雷的解析服务器，继续使用极速版。

    1、编辑文件 C:\Windows\System32\drivers\etc\hosts

    # ThunderSpeed DNS Verification Cheat 
    127.0.0.1 hub5btmain.sandai.net
    127.0.0.1 hub5emu.sandai.net
    127.0.0.1 upgrade.xl9.xunlei.com
    
    2、退出迅雷极速版并清掉后台残余进程。
    3、最后使用快捷键win+R并输入cmd，然后回车，在命令行中执行
    ipconfig /flushdns
    刷新DNS解析缓存！


迅雷极速版
``````````
.. code-block:: rst

    1、无广告：抛弃迅雷7三俗广告，去除游戏及新闻弹幕广，追求极简之美。
    2、无插件：抛弃其它产品捆绑安装，去除迅雷看看及游戏插件，无插件，启动更快。
    3、下载快：回归下载本质，优化产品架构及服务，专注下载，所以更快。