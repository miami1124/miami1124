<p align="center">
  <img src="assets/hero-sinica.jpg" alt="在中央研究院分享「非工程師的 AI 自動化」，畫面下方的即時英文字幕由自製工具產生" width="80%">
</p>

<p align="center"><sub>2026 年在中央研究院分享「非工程師的 AI 自動化」。畫面下方那行即時英文字幕，是我自己做的工具在跑。</sub></p>

# 張莆崧 SAM

我在新聞台做影音，然後開始把身邊的重複工作做成工具。

我不是工程師。我是那個每天坐在剪接台前趕時間、被同一件事煩到第三次，決定動手解決它的人。

---

## 關於我

做了幾年新聞影音，從上字幕、壓標題到盯上架。因為待過第一線，我很清楚哪些環節最耗時間、哪些最值得自動化。

我的做法是：把現場的抱怨拆成流程，跟 AI 一起開發、測試，再拿回去給真正的使用者用。判斷做完沒有的標準只有一個——**有沒有人每天願意打開它。**

現在專門研究怎麼把 AI 帶進新聞的工作流程，讓不同部門少做一點重複的事。

---

## 做過的東西

<table>
<tr>
<td width="40%" valign="top">

**[Live-Caption-Studio](https://github.com/miami1124/Live-Caption-Studio)**

台上講中文，台下即時看到英／日／韓文字幕，直接疊在你的簡報上。在自己電腦上跑，自備 Gemini API key。

中研院那場演講就是用它完成的。

</td>
<td width="60%">
<img src="assets/live-caption.jpg" width="100%">
</td>
</tr>

<tr>
<td width="40%" valign="top">

**影片 AI 摘要工具**（內部工具，未開源）

要抓一支拍帶的重點，以前得整支看完。現在貼上連結，2-3 分鐘拿到逐字稿加時間軸重點，還能用自然語言搜尋整個影片庫。

Modal + Groq Whisper + Gemini，加一套 RAG 檢索。

</td>
<td width="60%">
<img src="assets/video-analyzer.jpg" width="100%">
</td>
</tr>

<tr>
<td width="40%" valign="top">

**[subtitle-automation-pipeline](https://github.com/miami1124/subtitle-automation-pipeline)**

字幕國際化流水線：偵測到新的 SRT → AI 翻譯（含專有名詞保護）→ 整理時間軸 → 自動上傳、更新說明欄。

</td>
<td width="60%">
<img src="assets/subtitle-pipeline.jpg" width="100%">
</td>
</tr>

<tr>
<td width="40%" valign="top">

**[youtube-news-radar](https://github.com/miami1124/youtube-news-radar)**

每天自動掃台灣 YouTube 熱門影片，算熱度分數、AI 分類，推播給編輯台當選題參考。

</td>
<td width="60%">
<img src="assets/news-radar.jpg" width="100%">
</td>
</tr>

<tr>
<td width="40%" valign="top">

**[youtube-analytics-reporter](https://github.com/miami1124/youtube-analytics-reporter)**

頻道雙週報自動化：抓數據、統整分類、填進表單、LINE 通知。原本要人工整理半天。

</td>
<td width="60%">
<img src="assets/analytics-reporter.jpg" width="100%">
</td>
</tr>

<tr>
<td width="40%" valign="top">

**[guesthouse-booking-automation](https://github.com/miami1124/guesthouse-booking-automation)**

民宿預約單自動化（接案）。把客人的訂房訊息貼進 LINE Bot，AI 自動抓出姓名、日期、人數、房型，整理成預約單並回覆確認。省掉手動打字建檔那一段。

</td>
<td width="60%">
<img src="assets/guesthouse.jpg" width="100%">
</td>
</tr>
</table>

還有一個 [line-bot-ai-diet-coach](https://github.com/miami1124/line-bot-ai-diet-coach)：拍照辨識熱量、每日結算、自動提醒。自己用的，目前停用。

---

## 走過來的路

| 年份 | 做了什麼 |
|:--|:--|
| 2025 | 受不了重複工作，開始學 n8n。第一個工作流上線，同事真的在用 |
| 2026 上半 | 影片 AI 摘要工具上線，成為部門日常工具；受邀到中央研究院分享「非工程師的 AI 自動化」，用自己做的即時翻譯字幕完成整場演講 |
| 2026 下半 | 轉做 AI 應用規劃，把 AI 帶進各部門的工作流程 |

---

## 我怎麼工作

- **和 AI 一起寫，不是自己從零寫。** 我的價值不在敲鍵盤，在把講不清楚的痛點整理成做得出來的需求。
- **只做有人用的東西。** 沒人每天打開的工具，對我來說就是沒做完。
- **從第一線出發。** 我知道編輯缺什麼、記者急什麼，也知道工具只有真正融進工作流程才算數。

---

<p align="center">
  <img src="assets/n8n-badge.png" alt="n8n Quickstart 課程結業徽章" width="150">
</p>
<p align="center"><sub>n8n Quickstart 課程結業 · 2026/07</sub></p>

---

## 找我

正在找 AI 自動化 / AI 應用規劃的機會，正職或接案都可以聊。

📧 samchang176@gmail.com
