# AngryPanda-Game
## Game Engine: Unity 2018.4.6f1
## Game Source Code: https://drive.google.com/open?id=1j9F28gguQ4OuJMn-4E9q1tdLx9nCY2FH
## Game Download: https://drive.google.com/file/d/1l1ZoAcVFlBDDr4y5W50QF1mj42ZrUvG-/view?usp=sharing
## Demo Video: https://www.youtube.com/watch?v=9oxjwob-N4o

### 說明:
#### 1. 這個遊戲類似憤怒鳥，玩家的目的是透過投擲自己來殺死敵人。


玩家的投擲方式也類似憤怒鳥，主角被放在彈弓上，然後玩家拉著彈弓把自己射出去，然後撞向敵人到會觸發死亡的物件。


遊戲有分成三關，每一關都有特別的設計，使用特別的投擲方式可以一兩發就可以通關，其中第三關會有機關(殺了一定數量的敵人就可以觸發)，可見 demo 影片。


#### 2. 遊戲中底下有一個 UI 界面:


a. 左面用來顯示目前熊貓(主角)的數目，每死一隻熊貓就少了一發，每關共有十發。


b. 中間是敵人目前的數量，包括可惡的狗狗、豬豬、熊熊。


c. 右面是時間，有一分鐘時間，時間倒數到零後就會輸掉這個遊戲。


通關後，計算分數的公式:


剩下的時間多少就多少分數，如果時間>=50，就算成 50 分。


剩下熊貓 x5 倍分數


Score = Time + panda*5


#### 3. 主選單有一首歌，遊玩模式也有一首歌


音效:


a. 熊貓碰到物件音效


b. 拉弓音效


c. 投擲音效


d. 動物死亡音效


e. 過關成功音效


f. 過關失敗音效
