# 優質與地雷 Open Data 筆記列表
## 最近踩到的 Open Data 地雷實在太多，所以我用這個列表紀錄哪些 data 好？好在哪裡？歡迎 merge request
---
### 優質列表
有給到事件等級解析度：
- [104年臺中市舉發違反道路交通管理事件成果](http://data.gov.tw/node/41802)
    - 有每一次舉發事件的時間、方式、車輛規格、違反法規等細節

- [火災**事件**資料](http://data.gov.tw/node/13764)
    - 有民國 104 年台灣各縣市，單一火災事件的多個維度
    - 共 9 個欄位：[縣市, 鄉、鎮、市、區, 街、路段, 火災案件編號, 報案時間 (月：日：時：分) , 抵達時間 (月：日：時：分), 起火原因, 死亡人數, 受傷人數]

- [地震報告之歷史資料](http://data.gov.tw/node/12730)
    - 以單次地震事件為單位的資料
    - 欄位：[編號, 地震時間, 經度, 緯度, 深度, 規模, 震央位置]
    - 只來源只提供 web service，[這一份](台灣地震歷史_before_2017-0426(已前處裡).csv)是我自行前處理




### 地雷列表
只給統計量，資料太粗的：
- [106年台中市政府1999進線**統計**表](http://data.gov.tw/node/43029)
    - 只有民國 106 年 12 個月份的累積量，也就是只有 12 個 row 的資料
    - 共 6 個欄位：[進線總電話量, 客服人員應答數, 電話外撥數, 電話處理總數, 服務水準%, 平均通話時間]
  
- [104年臺中市消防緊急救護急救處置](http://data.gov.tw/node/41922)
    - 「58 個單位 x 26 種案件分類」的整年合計，沒有提供事件資料。 

---
