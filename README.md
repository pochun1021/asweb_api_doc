### 院網 api 文件
## v1.1.9
### 新增選單版型子選單

## v1.1.8
### 刪除函式 訂閱中研院訊

## v1.1.7
### 新增訂閱中研院訊語言
#### 異動
+ 訂閱中研院訊加入語言分類。

## v1.1.6
### 新增函式 訂閱中研院訊 [/subscribeNewsLetter]
#### 異動
+ 科普演講併入類別中，故移除欄位。

## v1.1.5
### 新增函式 取得行事曆資料 - 搜尋活動 [/getQueryEventData/{mID}]

## v1.1.4
### 新增參數 時間範圍
#### 異動
+ 取得行事曆資料 - 行事曆 [/getListCanlendarData/{mID}]
+ 取得行事曆資料 - 時間軸 [/getTimelineData/{mID}]

## v1.1.3
### 新增參數 組別
#### 異動
+ 新聞列表頁-table [/getNewlist/{mID}]
+ 新聞列表頁-cards [/getNewlistWithimg/{mID}]
+ 網路相簿 [/getGalleries/{mID}]
+ 影音 [/getVideos/{mID}]

## v1.1.2
### 新增參數 說明備註
description - 說明備註  
位置在 Response menus 及 menusEn 中
#### 異動
+ 新聞列表頁-table [/getNewlist/{mID}]
+ 新聞列表頁-cards [/getNewlistWithimg/{mID}]
+ 取得單篇新聞資料 [/getNewsData/{ID}]
+ 網路相簿 [/getGalleries/{mID}]
+ 影音 [/getVideos/{mID}]
+ 連續空7白版型 [/getParagraph/{mID}]
+ 頁籤版型 [/getTabs/{mID}]
+ 區塊版型 [/getSections/{mID}]
+ 多連結版型 [/getLinks/{mID}]
+ 選單版型 [/getDirectory/{mID}]
+ 人才招募列表 [/getRecruitmentlist/{mID}]
+ 取得單篇人才招募資料 [/getRecruitmentData/{ID}]
+ 取得行事曆資料 - 行事曆 [/getListCanlendarData/{mID}]
+ 取得行事曆資料 - 時間軸 [/getTimelineData/{mID}]
+ 取得單篇行事曆資料 [/getEventinfoData/{ID}]
+ 取得空白版型資料 [/getPage/{mID}]
+ 研究人員列表頁 [/Researcherlist/{mID}]
+ 取得研究人員資料 [/getResearcherData/{researcherID}]

## v1.1.1
### 修正參數名稱
#### 參數名稱異動
+ startData &rarr; startDate
+ endData &rarr; endDate
#### 異動
+ 取得行事曆資料 - 行事曆 [/getListCanlendarData/{mID}]
+ 取得行事曆資料 - 時間軸 [/getTimelineData/{mID}]
+ 網路相簿 [/getGalleries/{mID}]
+ 新聞列表頁-table [/getNewlist/{mID}]
+ 新聞列表頁-cards [/getNewlistWithimg/{mID}]
+ 影音 [/getVideos/{mID}]

## v1.1.0
### 新增人才招募相關 api  
#### 新增
+ 取得工作地點 [/getWorkAreaData]
+ 取得學經歷 [/getExpRequireData]
+ 取得工作類別 [/getWorkTypeCatData]
+ 取得職位 [/getWorkTypeData]
+ 取得職缺關鍵字 [/getJobOpeningKeywordData]  
#### 異動
+ 人才招募列表 [/getRecruitmentlist/{mID}]

## v1.0.0