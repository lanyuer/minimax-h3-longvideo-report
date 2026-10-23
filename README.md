# MiniMax H3 连续/长视频社区方案调研报告

非官方社区调研静态站（GitHub Pages 单页）。中文为主。视觉为浅色阅读风，移动端优先。

## 内容

- `index.html`：完整报告（分类导航、团队收口备注、方案说明、优缺点、共识、可播放 demo、来源）
- `assets/`：预留目录（本版优先外链嵌入公开 mp4，不打包版权不明大视频）

## 本地预览

```bash
cd /workspace/minimax-h3-longvideo-report
python -m http.server 8765
```

浏览器打开：<http://127.0.0.1:8765/>

也可直接打开 `index.html`（部分外链视频/iframe 在 `file://` 下可能受限，建议用 http.server）。

## 公开访问

- Pages：https://lanyuer.github.io/minimax-h3-longvideo-report/
- 仓库：https://github.com/lanyuer/minimax-h3-longvideo-report

## 调研说明

- 日期：2026-10-23（Asia/Taipei）
- 范围：Reddit、GitHub、Hugging Face、Bilibili、YouTube、Pruna API 文档等
- 原则：不伪造视频链接或评测数字；无公开直链处标注来源页与限制
- 阶段：调研收口；本机不跑模、不落地实现

## 许可与免责

页面内容为公开信息汇总，不构成官方文档。引用的第三方仓库、模型、视频仍归原作者与原协议所有。商用请自行核对 MiniMax / Comfy 许可。
