# TranslatorX-other
原来的 TranslatorX 更改为仅发布 JetBrains，所以独立出一个仓库处理自己平常的翻译。

# 项目结构
项目中又分为了很多子项目  
以及一个 miscellaneous 杂项，用来翻译单个或较少文件  
还有一个 template 模板

确定要翻译的文件应该放在一个子项目还是 miscellaneous 中？
* 如果文件较多，或者涉及专用的词汇表、片段分割或文件过滤器，为了不影响其他文件，应该列为子项目
* 如果文件较少，并且使用通用的词汇表、片段分割和文件过滤器，不会影响到其他文件，可以放于 miscellaneous 中