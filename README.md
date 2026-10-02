# 給軟體工廠裝三道煞車，PR 才審得完

Matt Pocock 在 AI Engineer Paris 2026 的演講〈Fixing the PR Bottleneck〉的深度導讀。

網頁：https://lushinshang.github.io/matt-pocock-fixing-pr-bottleneck/

## 200字介紹

AI 代理人讓 PR 數量大增，人類審查成為瓶頸。Matt Pocock 的主張是替軟體工廠裝三道煞車：自動檢查便宜但會說謊，自動審查要把編碼標準放給審查代理人而非實作代理人，人類審查則只對單向門審到底，並用 PR 底部的 Merge Danger 標出門的種類與影響範圍。最後用 retro 把每次審查的發現變成下一次的檢查與標準，讓同一則留言不必寫兩次。本文把講者的主張、他公開的 skills 儲存庫現況與引用的原始出處分開寫，並標出哪些是導讀者補充。

## 檔案

| 檔案 | 說明 |
|---|---|
| `index.html` | 單檔網頁，可直接用瀏覽器開啟 |
| `matt-pocock-fixing-pr-bottleneck.md` | 深度導讀 Markdown 原稿 |
| `images/web/` | 全景圖與三張章節配圖（WebP，各有桌面 16:9 與手機 9:16） |
| `images/hero/og_1200x630.png` | 連結分享預覽用的封面圖 |

## 原始資料

- 影片：[Fixing the PR Bottleneck — Matt Pocock, AIHero](https://www.youtube.com/watch?v=LlgiOCmFG_w)（頻道 AI Engineer，約 22 分鐘）

## 重要來源

- [mattpocock/skills](https://github.com/mattpocock/skills) 的 `improve-codebase-architecture`、`code-review`、`pr`、`retro`
- [humanlayer/skills 的 show-me](https://github.com/humanlayer/skills/blob/main/plugins/show-me/skills/show-me/SKILL.md)
- [Amazon 2015 年致股東信（Jeff Bezos）](https://s2.q4cdn.com/299287126/files/doc_financials/annual/2015-Letter-to-Shareholders.PDF)
- [AI Engineer Paris 2026 議程](https://ai.engineer/paris/2026)
- [John Ousterhout：A Philosophy of Software Design](https://web.stanford.edu/~ouster/cgi-bin/book.php)

## 收錄原則

講者的主張與可驗證的事實分開寫。標註「現行 repo」的內容，是 2026-10-02 查閱 GitHub 所得，演講中沒有提到。講者的個人觀察與推論保留為講者說法。

## 圖片

全景圖與三張章節配圖由 AI 圖像工具依導讀內容生成，圖內只放文章已確認的重點。

## 已知限制

- v1.3：演講中宣布本週發布。截至 2026-10-02，release/v1.3 的 PR 已合併，但套件版本號與 Releases 仍是 v1.2.3。
- 本頁為依公開演講與公開原始檔整理的導讀，非 Matt Pocock 或 AI Engineer 官方內容。

## 狀態

已發布：https://lushinshang.github.io/matt-pocock-fixing-pr-bottleneck/（發布日期 2026-10-03）
