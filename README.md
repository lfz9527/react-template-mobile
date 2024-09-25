<h1 align="center">react 移动端模板</h1>
<br/>

<br>

## 👨🏻‍💻 项目说明

-   PC 端模板：[react-enterprise-template](https://github.com/guokaigdg/react-enterprise-template)

-   react 模板, 一个比 CRA 更丰富的模板

-   开发配置文档说明 [React18 + webpack5 + TypeScript4 + react-router-dom + Mobx](https://juejin.cn/post/7197790401495121977)

-   项目创建教程 [《从 0 到 1 搭建一个 React 项目开发模板 》](https://juejin.cn/post/7223267430231326778)

## 📱 特点

-   📦 开箱即用，无需配置
-   📝 全面注释说明，学习低成本
-   🚀 启动编译迅速
-   🌱 极易定制, 拓展容易

## 🚀 技术栈

[![react](https://img.shields.io/badge/react-18.2.0-brightgreen.svg)](https://github.com/facebook/react/) [![TypeScript](https://img.shields.io/badge/TypeScript-4.9.4-brightgreen.svg)](https://github.com/microsoft/TypeScript)[![webpack](https://img.shields.io/badge/webpack-5.75.0-brightgreen.svg)](https://github.com/facebook/react/) [![axios](https://img.shields.io/badge/axios-0.18.0-brightgreen.svg)](https://github.com/axios/axios) [![mobx](https://img.shields.io/badge/mobx-6.8.0-brightgreen.svg)](https://github.com/mobx) [![react-router-dom](https://img.shields.io/badge/react--router--dom-6.8.1-brightgreen.svg)](https://github.com/remix-run/react-router) [![MIT](https://img.shields.io/badge/license-MIT-brightgreen.svg)]()

-   React v18
-   react-dom v18
-   TypeScript v4
-   webpack v5
-   axios v1
-   mobx v6
-   mobx-react-lite v3
-   react-router-dom v6

## ⌛️ 安装项目依赖

-   `node` >= 16.0.0
-   `npm` >= 7.0.0
-   `yarn` >= 1.22.17

```
npm
$ npm install

yarn
$ yarn
```

## 🚀 运行项目

```
npm
$ npm run start

yarn
$ yarn dev
```

## 📦 打包编译

```
npm run build:qa  // 测试环境
npm run build:prod  // 线上环境
```

## 代码提交规范

```
git <type>: <subject>
git commit -m “feat: 项目初始化”
```

### type 参考:

```
fix       🐛 Bug修复
feature   ✨ 引入新特性
docs      📝 文档书写改动
prune     🔥 移除代码或文件
ui        💄 更新UI和样式文件
perf      ⚡ 性能相关优化
rocket    🚀 部署功能
style     🎨 style修改
init      🎉 初始化提交
release   🔖 发布版本
wip       🚧 正在进行中, 且有可能出现不稳定运行的提交
config    🔧 修改配置文件
refactot  🔨 重构(既不增加新功能, 也不修改bug的代码改动)
merge     🔀 合并分支
```

## 📂 目录结构

```
    ├── .vscode
    │   └──setting.json                 # 先于vscode全局的settings.json配置
    ├── doc                             # 开发文档记录
    ├── webpack                         # 打包编译
    │   └──config                       # webpack配置
    │       ├── webpack.common.js       # 基础配置
    │       ├── webpack.dev.js          # 开发环境配置
    │       └──webpack.prod.js          # 生产环境配置
    ├── pubilc
    │   ├──favicon.ico                  # HTML图标
    │   └──index.html                   # HTML入口模板
    ├── src
    |   ├── api                         # 接口配置
    |   ├── assets                      # 静态资源
    │   ├── components                  # 项目通用通用组件
    │   ├── http                        # 请求统一封装
    │   ├── httpinterface               # ts类型定义
    │   ├── constData                   # 系统内的常量列表
    │   ├── router                      # 统一路由入口
    │   ├── store                       # 数据共享
    │   ├── styles                      # 全局样式
    │   ├── utils                       # 工具库
    │   ├── view                        # 页面
    │   ├── App.tsx                     # 主界面
    │   └──index.tsx                    # 入口文件
    ├── .babelrc.js                     # babel配置
    ├── .editorconfig                   # 跨编辑器维护一致编码风格
    ├── .env.json                       # 环境变量配置
    ├── .eslintignore                   # ESLint忽略检测文件
    ├── .eslintrc.js                    # ESLint配置
    ├── .gitignore                      # git提交忽略文件
    ├── .npmrc
    ├── .prettierignore                 # prettierc忽略文件
    ├── .prettierrc                     # prettierc配置
    ├── .stylelintrc.js                 # 代码风格配置
    ├── LICENSE                         # 开源协议
    ├── package-lock.json               # npm安装包锁定管理
    ├── package.json                    # 依赖包管理
    ├── README.md                       # 项目说明
    ├── tsconfig.json                   # ts配置文件
    └── yarn.lock                       # yarn安装包锁定管理

```
