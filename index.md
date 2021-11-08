YUN-TING LAI’s collections

# 功能開發 | 2020.10-Present

### 集保戶股權分散系統  [[code]](https://github.com/lisa4930007/ownership_distribution_access_db)
- 為案主進行需求分析與確認執行工具軟體，以說明文件作為與案主確認需求之媒介
- 撰寫爬蟲以蒐集股權分散公開資料，並匯入資料至Office Access 關聯式資料庫，再依匯出條件整理所需報表、圖表儲存至Excel
- 撰寫bash script且建立Windows定時工作排程，可完成每週自動爬蟲及匯入資料庫
- 程式撰寫風格符合PEP8編碼規範

### GCP API Speech-to-Text  [[code]](https://gist.github.com/lisa4930007/7ae7126fc4269b2260490e1b000935a3)
為聽打逐字稿需求撰寫Python script，使用GCP Speech-to-Text 語音轉文字API並透過Google Cloud Storage傳遞大型聲音資料，最終節省8成時間!

### .mat檔轉成yolo檔格式  [[code]](https://gist.github.com/lisa4930007/9af1c0d2832e77a7454d3ed9f6fca9c2)

### Python爬蟲開發
1. 爬取各股股票交易日收盤價，計算目標日於 N 日 (3, 5, 20, 60, 120, 240) 內達創新高股價之股票，整理至 excel 檔。 <br/>
[[案件spec]](https://reurl.cc/R6YL1z) | [[code]](https://gist.github.com/lisa4930007/3bb27a1e5e40af7d67c3085749b1bd9d)
2. 爬取 dcard 內文、留言，整理至 excel 檔。<br/>
[[作品連結]](https://reurl.cc/a5oNO4) | [[code]](https://gist.github.com/lisa4930007/a196bd9882bcd4ffbbfda05da9724622)
3. 爬國泰、元大、富邦等網站的匯率，可做每日自動爬資料功能，並整理為所需的格式、匯出到 csv 檔。<br/>
[[作品連結]](https://reurl.cc/l0Yppd) | [[code]](https://gist.github.com/lisa4930007/dc423f78cf8f8daf842c451ab6cd52e8)
4. 爬取債券網站所有月份之 csv 檔案，整理格式匯出至 excel 檔。<br/>
[[作品連結]](https://reurl.cc/jqNgLM) | [[code]](https://gist.github.com/lisa4930007/361d9a55d048e2ab3a0606c3eb3d6ee3)



# 網站開發 | 2020.10-Present

### (建置中) Django部落格 [[code]](https://github.com/lisa4930007/django-sweet-home)
<b>Demo: </b> https://django-sweet-home.herokuapp.com/
- 網站框架(Django)、後端工具(Python, Postgresql)、前端工具(CSS, Bootstrap)
- 貼文&留言板 CRUD、響應式網頁設計、登入登出功能、使用者權限與驗證、整合第三方API (如: Facebook登入)、單元測試、SMTP郵件服務等
- 部署至Heroku


### (建置中) Django錄音機網站
- 網站框架(Django)、後端工具(Python, MySQL)、前端工具(Vue.js, Bootstrap)
- 後端使用Django REST framework開發APIs 與前端交換資料，達到前後端分離
- 響應式網頁設計、登入登出功能、使用者權限與驗證、Vue.js 元件、前台後台UI、整合第三方API (如: Facebook登入)、單元測試、SMTP郵件服務、CORS設定等


![one_recorder_示意](https://user-images.githubusercontent.com/14839962/117851557-035c3300-b2b9-11eb-823d-dba9b7c4c7e2.png)



# 碩士班專案 | 2017.9-2020.1

### 碩士論文  [[論文連結]](https://drive.google.com/file/d/1riS2ZRwsAK0zWpvBbauF_OQCu7yfMdUV/view?usp=sharing)
「針對女性頭聲、混偏頭聲、混偏胸聲、胸聲區 音聲的分析與分類」<br/>
- 參與 2019 國際電腦音樂暨音訊技術研討會  [[Paper連結]](https://drive.google.com/file/d/1FslitxCjTyNMNt1GUDr--phr_bUYqFzE/view?usp=sharing)<br/>
- 作品曾展示於 2020 美國國際消費性電子展 (CES)

<p>研究動機：對於初學歌唱者，在演唱中辨識和控制聲區是一項困難的事情，因此，本篇論文將研究女歌手於頭聲、混偏頭聲、混偏胸聲、胸聲區的音聲，盼能藉由建立穩健、高準確率的聲區分類模型以幫助歌手學習歌唱。</p>
<p>研究方法與結果：在本研究中，首先充分討論了四種聲區的定義，接著，錄下三位女歌手演繹各聲區的音聲並交由兩位評審標註資料，再將這些音檔的每個時幀利用 WORLD 語音合成工具取出「梅爾倒頻譜係數」(MCC)、「帶狀非週期性的頻譜包絡」(BAP)和「基本頻率」(F0)，接著利用兩種機器學習演算法（支持向量機 SVM 和多層感知機 MLP ）進行分類，最後分別得到平均準確率為 70% 及 68% 的實驗結果。</p>

<p>Tools: Python, Machine Learning (SVM/MLP), Scikit-Learn, Pandas, Matplotlib</p>

### Text-to-Song 專案
“Examining The Influence Of Word Tonality On Pitch Contours When Singing In Mandarin.”  [[Paper連結]](https://drive.google.com/file/d/1YMwhpouMPATjJBI5g-RJPTN9s21sUg5p/view?usp=sharing) <br/>
_Oriental COCOSDA 2018 Best Student Award_

### 音樂資訊檢索 (Music Information Retrieval)
1. 節拍預測、節拍偵測 (beat tracking)、音符變化偵測 (onset detection)
2. 音高偵測、和弦偵測
3. Real-time音高偵測與即時通知提醒 (GUI demo)

![圖片 1](https://user-images.githubusercontent.com/14839962/117907845-11866f80-b30a-11eb-81ba-ca119ce94b0b.png)



# Graduation capstone in college | 2014.6-2015.6
「實作HTML5於類3D線上展覽室」 [[Work link]](https://drive.google.com/file/d/18pJSgmHkTLm5NuR16cgqb89M6FUw6pMl/view?usp=sharing)
- Team leader (led a 5-member team on the gratuate project)
- Project planning and team member coordination
- Coding and developing using Html5, CSS, Javascript, jQuery, WebGL, PHP and MySQL
