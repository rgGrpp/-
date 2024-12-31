如何展示你的架構 - "4+1"視圖

組員:10824201 黃光清

4+1”視圖是對邏輯架構進行描述，最早由 Philippe Kruchten 提出，他在1995年的《IEEE Software》上發表了一篇題為《The 4+1 View Model of Architecture》的論文，引起了業界的極大關注，現在已經成為軟體設計的結構標準 - 百度百科
總的來說，只要你去做彙報/寫PPT，你總是要畫上一兩個視圖的。
4代表了4種視圖，1表示基於某一個場景，結合4種視圖進行說明。

1.邏輯視圖（Logical View）
設計的對象模型，改成了用UML來表示。
![image](https://github.com/rgGrpp/-/blob/main/%E9%82%8F%E8%BC%AF%E8%A6%96%E5%9C%96.png)
邏輯視圖｜設計的對象模型

2.過程/進程視圖（Process View）
捕捉設計的並發和同步特徵。這個圖有點抽象，主要需要表現出線程、進程之間的關係。
![image](https://github.com/rgGrpp/-/blob/main/%E9%81%8E%E7%A8%8B%E8%A6%96%E5%9C%96.png)
過程/進程視圖

3.物理視圖（Physical View）
描述了軟體到硬體的映射，反映了分佈式特性。你的物理網路如何搭建。
![image]()
物理視圖

4.開發視圖（Development View）
描述了在開發環境中軟體的靜態組織結構。包含哪些功能模組。
![image](https://github.com/rgGrpp/-/blob/main/%E9%96%8B%E7%99%BC%E8%A6%96%E5%9C%96.png)
開發視圖

