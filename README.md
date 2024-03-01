# Dynamic clock

- 利用JavaScript中的Date來取得當前的時間，並透過計算動態旋轉，更新時、分、秒的位置，形成一個模擬的時鐘錶盤。


## :small_blue_diamond: Implementation:
- 基於 Date 物件： 透過JavaScript中的Date物件取得目前的時間訊息，包括年、月、日、時、分、秒等。

- 數學計算：透過正弦和餘弦函數，計算時、分、秒針的位置，並將其動態更新到時鐘錶盤上。

- 使用HTML和CSS創建了時鐘錶盤的視覺效果，並透過JavaScript動態更新其中的時、分、秒指針。

- 定時器更新： 使用setInterval()，每隔一段時間（10毫秒）呼叫一次函數，實現時鐘的即時更新。

### :small_blue_diamond: Result:
> ![](https://github.com/jaifenny/Dynamic_clock/blob/main/1.png)


          
