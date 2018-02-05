# NTU_FGC

科技大擂台 與 AI 對話 (正式賽): https://www.youtube.com/watch?v=W0O9L-2Gz3Y

 - NLP 回應對話範例程式: https://github.com/NTU-CSX-Project/R05631018/tree/master/Novel_Writer

1. CLOUD SPEECH API 語音轉文字採用機器學習技術: https://cloud.google.com/speech/?hl=zh-tw

2. NLP 語意理解學習菜單: http://cs224d.stanford.edu/syllabus.html

3. NLP 語意理解線上課程: https://www.youtube.com/playlist?list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6

# 未來預計進行方式:

1. 輪流認領學習菜單中的投影片內容，並完成相關作業

2. 實際測試 Kaggle 上的語料對話集:

    (1) https://www.kaggle.com/c/ntu-nlp-2017-term-project-1
    
    (2) https://www.kaggle.com/c/ntu-nlp-2017-term-project-2
    
    (3) https://www.kaggle.com/c/ml-2017fall-final-tv-conversation/data
   
    (4) 分頭收集資料集 [2018-03-05 當周收集完所有語料庫]
    
    - 小說類? 電子書
    
    - 日常生活? 我們這一家 (劇本)
    
    - 動畫卡通? 櫻桃小丸子, 蠟筆小新...
  
    - 聊天機器人對話集?
    
    - 國語測驗題
   
    - 簡體語料庫: https://github.com/candlewill/Dialog_Corpus
    
    - 字幕下載: https://kknews.cc/news/6k2glkp.html
    
    - 未分類對話者格式參考: 
    https://github.com/NTU-CSX-Project/R05631018/blob/master/Final_Chat-Bot/Data/training_data/1_train.txt

    - 訪談? 辯論? (第二階段): 
    使用 YOUTUBE 字幕下載器 http://k19980720.pixnet.net/blog/post/213690310-%E3%80%90youtube-cc%E5%AD%97%E5%B9%95%E4%B8%8B%E8%BC%89%E3%80%91%E7%B7%9A%E4%B8%8A-%E5%85%8D%E5%AE%89%E8%A3%9D%E8%BB%9F%E9%AB%94%EF%BC%8C%E7%9B%B4%E6%8E%A5

3. 預測模型產生的答案與題目的選項進行 seq2seq 轉化成向量後，做歐氏幾何距離或餘弦定理比對

# 實作套件建議:

1. http://pytorch.org/

2. https://keras.io/

3. https://www.tensorflow.org/
