# 架構
```
| docker-compose.yaml
|- mongo # 當服務起來，自動生成, 不然原本是空的
| | *
|
|- mysql # 當服務起來，自動生成, 不然原本是空的
|
|- redis # 當服務起來，自動生成, 不然原本是空的
| | *
|
|- express # 這是使用express 套件後 安裝的模組 ` npm install express --save `
| |- node_modules
| |  Dockerfile # 在外部頁籤可以看到 dockerfile 內容
| |  index.js
| |  package-lock.json
| |  package.json
|
|- react # 這是使用express 套件後 安裝的模組 ` npx create-next-app@latest `
| |- .next
| |- node_modules
| |- public
| |- src
| |  .eslintrc.json
| |  .gitignore
| |  Dockerfile
| |  next.config.mjs
| |  postcss.config.mjs
| |  tailwind.config.js
| |  README.md
|
```
