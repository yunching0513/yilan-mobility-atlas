# Yilan Mobility Atlas — 01 Traffic Safety

宜蘭縣交通安全地圖｜十年回顧（民 105–114 / 2016–2025）

互動式單頁地圖儀表板，以警政署 A1 級道路交通事故開放資料為基礎，呈現宜蘭縣十年的死亡事故空間分布、年度趨勢、熱力圖與優先治理路段。

## 線上預覽

GitHub Pages：`https://yunching0513.github.io/yilan-mobility-atlas/`

姊妹專案：
- [Taitung Mobility Atlas](https://github.com/yunching0513/taitung-mobility-atlas) — 台東縣
- [Tainan Mobility Atlas](https://github.com/yunching0513/tainan-mobility-atlas) — 台南市
- [Taipei Mobility Atlas](https://github.com/yunching0513/taipei-mobility-atlas) — 台北市

## 主要觀察（十年累計）

- **527 人** 在宜蘭道路上死亡，年均 53 人；2021 年峰值 69 人
- 弱勢用路人合計 **86%**（機車 63% + 行人 13% + 慢車 10%）
- **慢車（自行車）受害 10%**，目前四市最高 — 反映宜蘭觀光騎乘風氣
- 道路結構偏鄉村：省道 + 村里道路合計 42%（**不是市區道路為主**）
- 鄉鎮死亡前五：**宜蘭市 80、三星 60、冬山 59、蘇澳 52、五結 47**
- 熱點：台 9 線蘇澳段 114k（2021 年 6 死 1 件重大事故）；多處鄉村路口

## 資料分類方法 — 受害者運具邏輯

事件以「**最弱勢用路人**」為類別（行人 > 自行車/慢車 > 機車 > 汽車）。
原始 A1 資料的 P1 順位（肇因主要當事者）保留於 `principal_mode` 欄位。

## 資料來源

[內政部警政署 A1 級交通事故公開資料](https://www.npa.gov.tw/) ·
透過 [data.gov.tw](https://data.gov.tw/) 取得

## 開發者

吳昀慶 · Designed for 宜蘭縣交通安全分析

## 授權

程式碼：MIT。資料：依政府資料開放平臺授權條款。
