# PhantomLoaderQQNT 插件列表

本仓库维护 [PhantomLoaderQQNT](https://github.com/mlbv/PhantomLoaderQQNT) 的插件来源列表。[插件列表查看器](https://github.com/mlbv/LL-plugin-list-viewer)读取 `plugins.json`，从各插件仓库获取清单，并下载发行版或源码包。

列表优先提供已发布的 PhantomLoader 移植版：防撤回、修改图片概要、插件列表查看、PGP 加密和 Chii DevTools。其余条目已核对 Windows 平台和 LiteLoader manifest v4；PhantomLoader 保留 LiteLoader 5.2.1 API，但 QQ 页面结构和内部接口的兼容性仍取决于各插件，收录不代表已逐项完成运行测试。

添加插件时，向 `plugins.json` 末尾追加仓库和分支条目，再提交 PR：

```json
{
    "repo": "owner/plugin-repository",
    "branch": "main"
}
```

指定分支应提供 `manifest.json`，或在 `package.json` 中提供 `liteloader_manifest`。

列表基于 [LiteLoaderQQNT/Plugin-List 的 v4 分支](https://github.com/LiteLoaderQQNT/Plugin-List/tree/v4)，沿用 [MIT 许可证](LICENSE)。
