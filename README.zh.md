# Cubism Web Framework

Live2D Cubism 4 Editor 是一个用于输出模型的框架。

它提供了用于显示和操作模型的各种功能。
结合 Live2D Cubism Core 来加载模型。

通过构建（这个项目），您可以在浏览器使用这个 js 库。


## License

使用 SDK 前请确认 [License](LICENSE.md)。


## 开发环境

### Node.js

* 17.2.0
* 16.13.1
* 14.18.2
* 12.22.7

### TypeScript

4.5.2


## 开发环境搭建

1. 安装 [Node.js] 和 [Visual Studio Code]
2. 在 Visual Studio Code 中打开此项目并安装推荐的扩展，可以打开拓展菜单输入 `@recommended` 来检查有哪些推荐安装的拓展。
3. 在命令面板（* View> Command Palette ... *）中输入 `> Tasks: Run Task` 来显示可以执行的命令列表。
4. `npm: install` 安装依赖

可以通过命令面板执行命令列表中的命令。通常地，我们也可以打开一个终端直接输入命令执行。

注意: 调试设置在 `.vscode/tasks.json` 中描述。

## 命令列表

### `npm: build`

构建源文件并输出到 `dist` 目录。

如果需要，您可以通过编辑 `tsconfig.json` 更改配置。

### `npm: test`

执行 TypeScript 的类型检查。

如果需要，您可以通过编辑 `tsconfig.json` 更改配置。

### `npm: lint`

对 `src` 目录中的 ts 文件进行静态分析。

如果需要，您可以通过编辑 `.eslintrc.yml` 更改配置。


### `npm: lint:fix`

对 `src` 目录中的 ts 文件进行静态分析和自动修改

如果需要，您可以通过编辑 `.eslintrc.yml` 更改配置。

### `npm: clean`

删除构建输出目录（`dist`）。


## 部件（工程目录文件释义）

### effect

它提供了自动眨眼和唇形同步等功能，将运动信息作为效果添加到模型中。

### id

它提供了一个功能来管理使用唯一类型创建的参数名称、部件名称和 Drawable 名称。

### math

提供模型运算和绘图所需的算术运算功能，如矩阵计算和向量计算。

### model

它为处理模型提供了各种功能（生成、更新、销毁）。

### motion

它提供了各种功能（运动回放、参数混合）以将运动数据应用于模型。

### physics

提供将物理变换操作应用于模型的功能。

### rendering

提供一个渲染器，它实现了用于绘制模型的图形指令。

### type

提供在框架内使用的类型定义。

### utils

它提供了 JSON 解析器和日志输出等实用功能。


## Live2D Cubism Core for Web

这个库不包含 Cubism Core for Web。

如果您需要的话，可以从[Cubism SDK for Web]下载

[Cubism SDK for Web]: https://www.live2d.com/download/cubism-sdk/download-web/


## 样本

有关标准应用程序的示例实现，请参阅 [CubismWebSamples]。

[CubismWebSamples]: https://github.com/Live2D/CubismWebSamples


## 文档

[Cubism SDK Manual](https://docs.live2d.com/cubism-sdk-manual/top/)
> 强烈建议直接 debug [CubismWebSamples] 示例源码。

## 更改历史

更改历史详见 [CHANGELOG.md](CHANGELOG.md) 。


## コ社区

您可以通过社区进行建议，或询问有关如何在用户之间使用 Cubism SDK 的问题。

- [Live2D 官方社区](https://creatorsforum.live2d.com/)
- [Live2D community(English)](http://community.live2d.com/)
