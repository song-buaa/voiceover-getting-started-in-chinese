voiceover-getting-started-in-chinese
====================================

中文版苹果 VoiceOver 使用教程，请关注网站的无障碍设计

重复一遍，请关注网站的无障碍设计

原文地址：http://help.apple.com/voiceover/info/guide/10.9/English.lproj/index.html

# 翻译进度

认领中，请到https://github.com/numbbbbb/voiceover-getting-started-in-chinese/issues/1 回复认领


# 贡献力量

如果想做出贡献的话，你可以：

- 帮忙校对，挑错别字、病句等等
- 提出修改建议
- 帮忙修改内容，更适合阅读器阅读


# 翻译原则（重要）

请注意，你的目标读者对计算机的了解并不多，一定要从读者的角度出发来翻译。

尽量口语化，避免长句、难句。

只使用文字描述，读者很有可能使用的是阅读器，尽量方便他们阅读。

适当添加必要的说明，比如在表格的开头注明“下面是一个表格”或者“见下表”。

翻译结果使用markdown写，保存到source文件夹下的对应章节中，我最后会统一制作成方便阅读的版本。

# 翻译流程参考

有些朋友可能不太清楚如何帮忙翻译，我这里写一个简单的流程，大家可以参考一下：

1. 首先fork我的项目
2. 把fork过去的项目也就是你的项目clone到你的本地
3. 在命令行运行 `git branch develop` 来创建一个新分支
4. 运行 `git checkout develop` 来切换到新分支
5. 运行 `git remote add upstream https://github.com/numbbbbb/the-swift-programming-language-in-chinese.git` 把我的库添加为远端库
6. 运行 `git remote update`更新
7. 运行 `git fetch upstream gh-pages` 拉取我的库的更新到本地
8. 运行 `git rebase upstream/gh-pages` 将我的更新合并到你的分支

这是一个初始化流程，只需要做一遍就行，之后请一直在develop分支进行修改。

如果修改过程中我的库有了更新，请重复6、7、8步。

修改之后，首先push到你的库，然后登录GitHub，在你的库的首页可以看到一个 `pull request` 按钮，点击它，填写一些说明信息，然后提交即可。


# 开源协议
基于[WTFPL](http://en.wikipedia.org/wiki/WTFPL)协议开源。
