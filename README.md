## 冰羊猪扩展

启动方法：
1. 安装 git

[https://git-scm.com/](https://git-scm.com/)

2. 克隆项目

`git clone https://github.com/small-ruin/ice-sheep-boar`

3. 安装 node

[https://nodejs.org/zh-cn/](https://nodejs.org/zh-cn/)

4. 安装依赖

在项目目录中打开终端，然后执行：
`npm install`

5. 运行

```
// 启动服务，默认4000端口
npx gitbook serve

// build静态资源
npx gitbook serve
```

6. 如何修改页面：
在对应的 `md` 文件下修改。[markdown语法](https://www.markdown.cn/)。

`gitbook serve` 服务可以立刻看到结果。

静态资源需要重新打包。

7. 如何添加新页面：
  1. 在目录里添加对应的 `markdown` 文件;
  2. 在 `SUMMARY.md` 中添加路径;
  3. 如果是静态资源，需要重新打包部署;

