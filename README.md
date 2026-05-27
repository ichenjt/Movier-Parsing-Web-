# Movier.
Movier 是一個整合台灣多家影城場次資訊的電影查詢網站!
使用者可以先選擇縣市與區域，再選擇想看的電影，網站會整理出同一區域內不同影城的播放時間，減少逐一打開各影城官網查詢的麻煩。

## Website
https://movier-taiwan.streamlit.app/

## Features
- 依縣市與區域查詢電影場次
- 整合多家台灣影城資料
- 顯示同一部電影在不同影城的播放時間
- 點選場次後導向官方購票頁面
- 支援桌面與手機瀏覽

## Data Sources
目前整合全台四大影城：
- 威秀影城
- 秀泰影城
- 新光影城
- 國賓影城

## Tech Stack
- Python
- Streamlit
- Requests
- BeautifulSoup
- Playwright
- JSON data processing
- GitHub + Streamlit Community Cloud

## Motivation
這個專案源自於生成式人工智慧課程中「資料爬蟲」的單元
在日常生活中，查詢電影場次常需要分別打開不同影城網站，因此我嘗試透過爬蟲與 API 請求，將多家影城的電影資料與時刻表整理在同一個介面中讓查詢流程更直覺!

## Notes
本網站僅整理公開影城場次資訊  
實際訂票流程會導向各影城官方網站完成
