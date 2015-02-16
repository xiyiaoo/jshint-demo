# jshint 的使用


___
## 介绍
检验javascript的工具，以便有更加规范，良好的代码。

___
## 安装

- 首先需要安装nodejs
- 全局安装jshint `npm install -g jshint`

___
## 使用

```
#jshit --help查看帮助
#默认会在当前目录寻在.jshintrc，如果没有递归查找.jshintrc直到根目录。都没有则使用默认配置
jshit demo.js
#指定配置文件
jshit -c .jshintrc demo.js
```
___
## 一些属性的说明
见[官方文档](http://jshint.com/docs/options/)，[其他总结](http://www.zipeng.info/archives/jshint-intro.html)  

[sublime插件](https://github.com/victorporof/Sublime-JSHint)