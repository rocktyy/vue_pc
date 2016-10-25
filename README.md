# vue2

> A Vue.js PC project (vue-loader)

项目搭建

1.demo选择 (感谢)
https://aotu.io/notes/2016/10/13/vue2/?o2src=juejin&o2layout=compat

创建命令:

#npm install

#npm run dev

#npm run build

2.webpack  学习

/* dev 打开浏览器(HMR，模块热部署。)   build执行打包命令 */

"scripts": {
    "dev": "webpack-dev-server --open --inline --hot",
    "build": "cross-env NODE_ENV=production webpack --progress --hide-modules"
},

a. https://segmentfault.com/q/1010000005694821/a-1020000005702442   (npm run dev和build 介绍)
b. http://developer.51cto.com/art/201510/493477.htm      ( webpack详解 )
c.https://segmentfault.com/a/1190000005811347?_ea=934705   （使用cross-env解决跨平台设置NODE_ENV的问题）

3.如何降低Vue.js项目中Webpack打包文件的大小

a.http://blog.csdn.net/maray/article/details/50988500



