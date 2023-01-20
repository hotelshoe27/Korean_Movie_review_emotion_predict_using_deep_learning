# Korean_Movie_review_emotion_predict_using_deep_learning

***Korean movie review emotion prediction using deep learning***

This simple project predicts korean movie review based on naver movie review web.  
See requirements.txt before testing and check detail through source code👀  

---

## 1_Crawling  
![12](https://user-images.githubusercontent.com/120359150/213603825-a6841028-e624-43fc-9e20-0e008c3f6cfe.PNG)  
https://movie.naver.com/movie/point/af/list.naver  
Crawling upper web using 'Data_crawling.ipynb'  
❗This web pages is maybe limited 500 pages❗  

## 2_Labeling
This project case, using 3 label(0: Negative / 1: Positive / 2: Normal)  
But I recommend just using 2 label(0: Negatice / 1: Positive).  Because most reviews are 'positive', There is a data imbalance.  

## 3_Preprocessing & train  
See detail through this source code.  
In this project case, just used only Bi-LSTM. If you have a good idea, try applying!
