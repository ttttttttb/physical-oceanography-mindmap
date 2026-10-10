# 物理海洋学知识架构脑图（Physical Oceanography Mindmap）

物理海洋学教学用单页交互式脑图站点：以可缩放、可拖拽、可搜索的节点图组织“物理海洋学”知识体系，右侧联动显示每个知识块的说明、要点、公式与备注。

- **在线地址**：https://ttttttttb.github.io/physical-oceanography-mindmap/
- **本地预览**：双击 `index.html`，或在本目录执行 `npx serve .`
- **技术实现**：单文件 HTML + 内联 CSS/JS + SVG 连线；无外部依赖、无构建流程、可离线打开
- **源文件出处**：由 `outputs/physical-oceanography-mindmap.html` 拷贝而来（SHA256 一致）；此后本目录的 `index.html` 为线上唯一来源
- **交互**：拖拽平移、滚轮/按钮缩放、点击节点查看详情、折叠/展开分支、关键词搜索高亮、全屏适配

## 目录结构

```
index.html   页面本体（即站点根路径）
.nojekyll    关闭 Jekyll 处理，按纯静态发布
README.md    本文件
```

## 更新方式

```bash
git add -A
git commit -m "更新说明"
git push
```

推送后 1–2 分钟内 GitHub Pages 自动更新。

## 回滚

删除 GitHub 上的仓库即可下线站点；本地删除本目录即可。