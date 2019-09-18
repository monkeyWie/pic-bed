此仓库只做图片保存，使用 vs code + PicGo 作为图床客户端。

默认存储在`images/`目录下，修改 vs code `picgo.picBed.github.path` 配置，可以指定对应存储的目录。

在每个需要用到图床的项目下新建`./vscode/settings.json`文件来指定项目对应的存储目录：

```json
{
  "picgo.picBed.github.path": ""
}
```
