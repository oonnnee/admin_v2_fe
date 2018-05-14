###webpack

####前端资源打包工具
####在webpack中，每一个资源都是一个模块，都可以通过webpack打包到js中


###html-webpack-plugin

####自动生成一个html文件
####自动引入js
####生成的文件名字带hash，防止浏览器缓存


###babel

####转译es6


###babel-preset-react

####处理react语法，转译react


###css-loader

####加载css文件


###sass-loader

####加载sass文件


###style-loader

####处理成dom里的style标签


###url-loader, file-loader

####加载静态资源


###extract-text-webpack-plugin

####将style样式提取出来，也就是提取style-loader处理后的结果


###CommonsChunkPlugin

####webpack自带，通过它，可以将通用的模块抽取出来，放在一个单独的文件中


###webpack-dev-server

####使用它可以通过http的形式访问webpack打包好的文件
####监听文件的改动，自动刷新浏览器
####代理，路由的拦截和转发 ，只在当前项目中生效  charis拦截所有的请求