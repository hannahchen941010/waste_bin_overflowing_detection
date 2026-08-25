# 垃圾桶滿溢程度偵測 (Waste Bin Fill Level Detection)

本專案是在**香港教育大學**進行的 AI 專案，使用 YOLOv8 模型來自動偵測垃圾桶的滿溢狀態。

## 📌 辨識類別
專案可以辨識以下 4 種狀況：
* `empty`：空桶
* `half-full`：半滿
* `full`：已滿
* `overflowing`：滿溢（垃圾溢出）

## 📁 檔案說明
* `train/`：訓練用圖片
* `valid/`：驗證用圖片
* `test/`：測試用圖片
* `data.yaml`：模型設定檔
