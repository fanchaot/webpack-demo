
## webpack
 > 以前项目单独建几个文件 (html js css)   无法保证项目的可维护性  
 然后我们就把不同的业务逻辑拆成模块 分开引入 每个模块做自己的事情就可以保证项目的可维护性，可扩展性，但假如你有几千个模块，你能引入几千个JS文件吗？ 当项目大到这种程度的时候，我们需要借助工具来管理我们的模块了，webpack4 帮助我们管理复杂项目的工具 。 与webpack 相似的有 grunt gulp browserify   但是相比较webpack 的使用率直线上升，比如 VUE REACT ANGULAR使用webpakc 来做底层代码的构建，webpack 4 速度更快，大型项目节约90%构建时间，   内置了更多默认配置， 变更了许多的API
## Webpack 究竟是什么？产生的背景 能给我们带来什么

## 什么是模块打包工具？
## webpack 的正确安装方式
> node -> npm -> webpack
可以全局安装 npm  i webpack webpack-cli -g  
不推荐使用  多个项目之间可能使用的版本号不同 会导致项目运行不起来

## 使用Webpack的配置文件

> 该怎么打包
打包时候的文件哪个是入口文件 打包出的文件放在哪里 webpack 没有智能到你给它一个文件他就知道走或者是你给它一个项目他就知道怎么打包, 没有这么智能，他需要你给它一个配置文件告诉它应该怎么打包