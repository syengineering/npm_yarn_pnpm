# 对比  npm3 | npm4 | npm6 | npm8 | yarn | pnpm 安装依赖 express 目录分布
# npm2
```shell
node_modules_npm2
└── express
    ...
    ├── node_modules
    │   ├── accepts
    │   │   ├ ...
    │   │   ├── node_modules
    │   │   │   ├── mime-types
    │   │   │   ├ ...
    │   │   │   │   ├── node_modules
    │   │   │   │   │   └── mime-db
    ...
```

# npm3 | npm4 | npm6 | npm8 | yarn
```shell
node_modules_npm6
├── accepts
│   ├...
...
├── express
│   ...
...
```

# pnpm
```shell
node_modules_pnpm
└── express -> .pnpm/express@4.18.2/node_modules/express

1 directory, 0 files
```