# 住前走一遍

室内照片建模项目的只读展示站点。

- 漫游首页：https://zhonglaoban.github.io/zhongfan/
- 项目文档：https://zhonglaoban.github.io/zhongfan/docs/

首页自动载入当前发布的室内空间，支持拖动环视、点击地板或贴地地毯行走、键盘与触屏移动、小地图、暂停和回到起点。

顶部“文档”介绍上传、图片分析、Blender 建模、网页生成，以及各阶段的输入、输出与验收。文档内嵌截图，可阅读、编辑表格列宽、导出和打印。

线上暂不开放照片上传、AI 生成、对话调整和 Blender 更新，这些功能由本地工作台提供。本站没有本地 API、模型执行器或登录凭据。

## 发布

GitHub Pages 从 `main` 分支根目录发布。当前房间模型和导航位于 `room/`，文档位于 `docs/index.html`。`release.json` 记录快照版本及模型 SHA-256。本地工作台后续的修改不会自动发布。

当前房间：`71ffba85-5f89-461d-8a3a-8efae01ad604`

当前版本：`aa024a9c-9d1f-4d0a-9d7c-3b587a7540d6`
