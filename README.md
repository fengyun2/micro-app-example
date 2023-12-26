# micro-app-example


## 简介

基于 qiankun 实现的微前端应用示例。

## 运行

```bash
# 安装依赖
pnpm install

# 启动服务
pnpm start:all

# 访问
http://localhost:8080

# 构建
pnpm build:all
```

## 目录结构

```bash
.

├── README.md
├── package.json
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
├── packages
│   ├── vue3-main
│   │   ├── index.html
│   │   ├── index.js
│   │   └── package.json
│   ├── vue3-child
│   │   ├── index.html
│   │   ├── index.js
│   │   └── package.json
│   ├── vue2.7-main
│   │   ├── index.html
│   │   ├── index.js
│   │   └── package.json
│   └── react18-child
│       ├── index.html
│       ├── index.js
│       └── package.json
```

