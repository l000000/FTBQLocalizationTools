# ftbquestsAutoTrans
[English README](README.en.md)

介绍:

一个使用百度API批量翻译任务的简单python程序

本程序更替思路受项目 https://github.com/djacu/ftbquests_converter 启发，并在其框架基础上进行了大量更新与优化，对标当前最新ftbquest的任务生成格式

使用:

1. 复制粘贴`config_example.py`并将新文件重命名为`config.py`，配置`APPID`和`APPKEY`
2. 将ftbquest文件夹放到程序同级目录下运行程序

为了获取更好的翻译效果，建议先在百度翻译api中扩充自己的术语库
(原版术语可以参考：https://github.com/CFPAOrg/Glossary)

效果：
![image](https://img2023.cnblogs.com/blog/2192803/202301/2192803-20230107125912964-39430206.png)

PS:

如果你有更好的思路或者发现了某些bug，欢迎在此pr！
