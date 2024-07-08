## WebSocket Server Demo
解壓縮後直接執行 WebSocket.exe，若遇防火牆權限請點允許。
執行之後畫面中應會顯示
```
WebSocket server started on ws://localhost:7777/Chat
```
此時 Server 已經啟用，若在正確位址收到訊息將會於畫面中顯示，所有訊息都會帶上時間標記
若以其他裝置連線，或是連線時出現問題，可以試著將 localhost 更改為運行執行檔主機的 IP 位址
若須清除畫面中的訊息，可點擊畫面下方的Clear

## 訊息分類
### 1. Server建立成功
**WebSocket server started on ws://localhost:7777/Chat**
**WebSocket server listening...**
### 2. 收到 Client 連接訊息
**client connected from: [IP 位置]|[port]**
### 3. 收到 Client 離線訊息
**client disconnected from: [IP 位置]|[port]**
### 4. 收到一般訊息
**Message contnet**

## 示意圖
![WebSocket_JJryyDMJ65](https://hackmd.io/_uploads/rJ2ReBFP0.png)



