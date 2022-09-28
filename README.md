# MonFood
<pre>
這是一個就學期間寫的專題作品，主要內容為一個外送平台-MonFood，由七個組員共同完成。
我主要負責內容：

<strong>◉登入註冊 - 註冊資料即時驗證、自動發送信件驗證Email並生效註冊帳號。</strong>
MonFood/src/main/java/com/model/user
MonFood/src/main/java/mailservice/
MonFood/src/main/webapp/userRegister.html

<strong>◉外送系統 - 取得目前位置並串接Google Map APIs即時規畫路徑及預估車程時間。</strong>
MonFood/src/main/webapp/delDelivery.html

<strong>◉接單通知 - 利用WebSocket三方推播並接收餐點狀態。</strong>
MonFood/src/main/java/ws/push/ResToDel.java

<strong>◉後臺管理 - Ajax串接後端並對資料庫查找。</strong>
MonFood/src/main/java/com/model/administrator/
MonFood/src/main/webapp/adminRes.html

前端使用：JavaScript,jQuery,HTML5,CSS,RWD
前後端串接：Ajax
後端：Java,JSP
資料庫連線：JDBC
資料庫：MySQL,Redis
</pre>
