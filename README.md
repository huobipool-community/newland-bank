## 编译 Compile

```
npm install
truffle build
```

## 部署 Deploy

1. 在`networks`目录下修改不同环境的合约信息 Edit contract information for different environments in the `networks` folder
2. 修改`migrates`目录下文件中引用不同的networks文件 Edit references to different networks in the `migrates` folder files
3. `truffle migrate`
4. 将migrate最后输出的JSON字符串给前端,前端更新信息 Migrate the last output JSON string to the front-end, the front-end updates the information

## 调试 Test

```
truffle console
```
