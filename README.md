# pmc

monorepos

## 往根目录添加 package

ep: lerna add @zww/add --scope=monorepo-project
不加 scope 会全部都安装

### 初始化项目

git clone <path>
git submodule init
git submodule update
或 git clone --recursive <path>

### 普通更新

git submodule update

### 添加 subModule

git submodule add <local-absolute-path: b> <path>
