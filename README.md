# [react-web-pro](https://github.com/Joinbooks/react-web-demo)

基于 webpack 搭建的 React 打包开发模板


### 目录结构

```
├── build                   // webpack配置
│   ├── webpack.common.js   // webpack通用配置
│   ├── webpack.dev.js      // webpack开发环境配置
│   └── webpack.prod.js     // webpack生产环境配置
├── dist                    // 打包输出目录
├── public                  // 项目公开目录
├── src                     // src开发目录
│   ├── assets              // 静态资源
│   ├── components          // 公共组件
│   ├── layouts             // 页面布局组件
│   ├── modules             // 公共业务模块
│   ├── pages               // 具体业务页面
│   ├── routers             // 项目路由配置
│   ├── services            // axios服务等相关
│   ├── stores              // 全局公共 mobx store
│   ├── styles              // 存放公共样式
│   ├── utils               // 工具库/通用函数
│   ├── index.html          // 入口html页面
│   └── main.js             // 项目入口文件
├── .babelrc                // babel配置
├── .editorconfig           // 项目格式配置
├── .eslintrc.js            // ESLint配置
├── .gitignore              // git 忽略配置
├── .postcssrc.js           // postcss配置
├── package.json            // 依赖包配置
└── README.md               // 项目说明
```

## CLI 构建命令

### 克隆项目

```bash
git clone git@github.com:Joinbooks/react-web-demo.git
```

### 初始化依赖配置

```bash
yarn install
```

### 开发环境 启动运行

```bash
yarn start
```

### 生产环境 打包构建

```bash
yarn build  //生产环境 打包构建

yarn build:report // 图形化分析打包文件大小；

yarn build:watch // 方便排查生产环境打包后文件的错误信息（文件source map）；
```

## More
暂无
分支开启