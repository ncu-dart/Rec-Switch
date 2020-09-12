# Rec-Switch  
[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/wXV3CSZiQl-78b8fETp9EQ?view)  

本專案為《探索深度學習或簡易學習模型在點擊率預測任務中的使用時機》所使用之程式碼  
程式碼外之資料請參照各說明中的下載連結  

## 專案結構  

#### CTR_v5/ [說明](https://hackmd.io/HkY7MkTNRfWhVcrGG7r3Xw?view)  
- 處理台灣電商資料集122天的資料  
- 進行排序(Ranking)階段的實驗  
#### Taobao_v4/ [說明](https://hackmd.io/LlPx8ZzLQZ6vyfA9QSNMPg?view)  
- 處理淘寶資料集9天的資料  
- 進行排序(Ranking)階段的實驗  
#### Switch_task/ [說明](https://hackmd.io/6SFIXNY9Tb-p59ktlq0YRQ?view)  
- 進行Switch階段的實驗  
- 論文實驗數據皆在此階段進行產出  

## 專案實驗環境  
- OS：  
    - Distributor ID: Ubuntu  
    - Description:    Ubuntu 18.04.4 LTS  
    - Release:        18.04  
    - Codename:       bionic  
- Python 3.7.5  
    - gensim                  3.8.1  
    - imbalanced-learn        0.6.2  
    - jupyterlab              2.0.1  
    - Keras                   2.3.1  
    - matplotlib              3.1.1  
    - numpy                   1.17.2  
    - pandas                  1.0.3  
    - scikit-learn            0.22.2.post1  
    - scipy                   1.4.1  
    - tensorflow-gpu          2.1.0  
    - tqdm                    4.36.1  
    - xgboost                 1.0.2  