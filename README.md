# Portfolios-based-on-crowding  
Overview:
參考Zhong,L.(2017).The impact on stock returns of crowding by mutual funds.The journal of portfolio management:a publication of Institutional Investor, 43(4)  
共同基金汲於挖掘獲利機會，以追求相對報酬，因此容易產生共同基金在市場上使用類似的策略，而形成交易擁擠(crowded trades)現象，而擁擠度和流動性的差別是流動性只有考慮到換手率(turnover)，而擁擠度則是同時考慮到換手率和機構持股比率兩個因素。  
衡量擁擠度的指標為Actratio，使用的是主動管理基金的數據，因為主動管理基金相比被動管理基金更傾向於使用短期的策略或進行擇時。正因如此，基金經理們接收的信息相關性會較高，整體上更容易造成較為擁擠的交易。我們使用該指標判斷股票是否處於擁擠狀態，並設計了一個策略，試圖從交易擁擠中獲取超額收益。  
#策略建構  
1.透過蒐集2012~2021的台灣上市公司股價資料，檔案為stockdata1.csv，計算擁擠度指標Actratio  
2.計算報酬率矩陣並且依據擁擠度大小排序，分為10組  
3.列表出各組的Actratio、平均報酬、標準差  
#Markdown檔案可參考Portfolios-based-on-crowding.pdf  
