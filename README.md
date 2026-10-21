# NPO 營運健檢框架

給台灣社會團體（特別是以教育為主、志工密集的中小型 NPO）用的營運健檢框架：階段定位、十維度健檢、年度合規與規劃日曆。

網站：<https://leadfortaiwan26.github.io/operational-framework/>（GitHub Pages，`main` 分支 `/docs`）
姊妹框架：[任務管理健檢框架](https://github.com/leadfortaiwan26/task-management)

> v0.1 草稿。法規摘要是閱讀條文的整理，不是法律意見；使用前請對照全國法規資料庫原文。

## 更新方式

```bash
npm install
npm run build   # src/framework.md → docs/index.html
```

- 內容：`src/framework.md`。改完跑 `npm run build`，把 `src/` 與 `docs/` 一起 commit。
- 頁首文字與連結：`site.json`（要加頁面時在 `pages` 列出）；樣式：`style.css`（build 時複製到 `docs/assets/`）。
- 證據標記 `[F]` 事實、`[E]` 專家或機構主張、`[I]` 推論、`[H]` 未查證，build 時會轉成小標籤。
