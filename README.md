# Fractional Kaiser Window: FIR Filter Design & Implementation

## 專案簡介
本專案為數位訊號處理課程之期末研究，旨在復刻論文：
> **"Fractional Kaiser Window With Application to Finite Impulse Response Digital Filter Design"** {Kemal Avci (İzmir Democracy University), 2024}

## 實作內容
傳統的 Kaiser 窗是數位訊號處理中最常用的可調式窗函數之一 。本專案實作的新型窗函數引入了一個額外的分數階參數 ($\gamma$) ，使其在特定條件下（尤其是 $\gamma < 1$ 時）能提供比傳統 Kaiser 窗更窄的主瓣寬度與更小的波紋比 。


![workflow](images/fig1.png)

## 實驗結果
| 模型 | 論文 Log Loss | 我的實作 Log Loss |
| :--- | :--- | :--- |
| **Ensemble Model** | 0.13 | 0.26 |

## 復盤與心得(Technical Highlights:)

* **Deep Learning**: ResNet, Feature Extraction, Transfer Learning.

* **Machine Learning**: XGBoost, Ensemble Learning.

* **Data Processing**: SAR Image Pre-processing, Data Augmentation.

* **Evaluation**: Log Loss, 5-Fold Cross Validation analysis.
 
