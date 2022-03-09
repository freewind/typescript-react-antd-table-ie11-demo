TypeScript React AntDesign Table IE11 Demo
====================================================

antd似乎在IE11下也可以运行，前提是需要加上相应的polyfill:

```
import 'react-app-polyfill/ie11'
import 'react-app-polyfill/stable'
```

由于`react-app-polyfill/stable`里面引入的也是corejs，所以在webpack中使用`@babel/preset-env`+corejs也应该可以达到一样目的。

不过不知道是不是所有的组件都被支持

```
npm install
npm run demo
```

然后在windows下访问
