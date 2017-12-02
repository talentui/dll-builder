# 用于构建和打包Dll的模版项目

本模板项目已经集成到@talentui/cli中,在使用前确保你已经全局安装了`@talentui/cli`
```nodejs
yarn global add @talentui/cli
```

# 使用方法：
1. cli 初始化项目
```nodejs
talent init myDll
```

2. 选取 打包dll的模版项目

![image](https://user-images.githubusercontent.com/18530075/33510302-a0df7090-d745-11e7-8efc-e950c5ed316b.png)

3. 按照规则输入需要打包的依赖名称及其版本号

![image](https://user-images.githubusercontent.com/18530075/33510310-c57a8688-d745-11e7-8017-2f31cb923a82.png)


4. 按照提示完善后续项目信息

5. 项目创建完成后，执行
```javascript
yarn install //安装依赖
yarn build //开发环境打包dll
yarn build-prod//生产环境打包dll
```