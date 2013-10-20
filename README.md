OOSE, UML Case Study
====================

Object-Oriented Software Engineering, UML Case Study

Software Requirements:

* Astah Community [astah]

Outlines:

這份教材提供兩個案例練習。

1. Pet Clinic (2 weeks)
2. Mobile Tickets (4 weeks)

（案例描述中的故事情節純屬虛構）

課程進行方式：

1. 分組
2. 任務角色分工

由同學自行分組（約 3-5 人）成立專案開發團隊，
需要分別有人員負責專案經理、系統分析師及程式設計師等角色。

* 團隊名稱
* 人員名單及職掌

以下個案交付專案團隊進行系統分析與設計任務，需在時限內交付成果報告。

### Pet Clinic Case Study ###

Pet Clinic 是一家寵物診所，從 2009 年開始提供網站服務顧客。
隨著業務不斷擴張，Pet Clinic 需要更多的網站附加功能，才能滿足更多顧客的需求。

然而協助 Pet Clinic 開發網站系統的網路公司已經歇業，將由本公司負責接手維護並開發新功能。

#### Scenario (1) ####

第一次專案成立會議記錄。

客戶（診所）：

目前診所網站的功能很陽春，僅可以查詢獸醫的資料，
並提供顧客（飼主）登記寵物資料。
我們想幫網站加入一些新功能，
需求等我們內部討論清楚再跟各位報告，
資料大概是明天中午再寄到貴公司電子郵件信箱。
這段時間就請你們先瞭解我們網站的架構吧！

經理：

由於原先負責開發 Pet Clinic 的公司已人去樓空，
系統開發的相關文件已無從索取，
我們目前沒有任何關於 Pet Clinic 網站的任何文件；
幸好診所還有保留一份網站伺服器的密碼與程式原始碼，
稍後請助理提供給各位參考。

助理：

Pet Clinic 的網址是：http://petclinic-grails.appspot.com/
完整程式碼已經上傳到 GitHub 網站。https://github.com/lyhcode/grails-petclinic

經理：

時間緊迫請各位同仁務必在下班前將相關文件資料補齊。

(--- 會議記錄結束 ---)

任務說明：

1. 瞭解網站使用什麼開發技術？網站的目錄結構包含哪些重要內容？
2. 請繪製網站的樹狀結構圖。
3. 請考慮有哪些使用者會利用這個網站？試著畫出使用案例圖（Use Case Diagram）。
4. 請分析現有的程式碼，找出有哪些實體（Entity），並用 UML 類別圖（Class Diagram）繪製。

#### Scenario (2) ####

客戶以電話通知。

    我們希望加入線上預約的功能，幫櫃台減少一些電話接聽次數。
    在寵物生日的時候，我們希望透過網站寄送電子賀卡。
    還有許多顧客抱怨網站速度太慢，我們老闆已經同意花一筆預算升級硬體。
    還有其他同仁給的意見我整理在郵件裡。

收到電子郵件。

    Dear _______,

    1. ooo
    2. ooo

    Best regards,
    Pet Clinic Administration Manager

任務說明：

1. 根據電話與郵件的說明，有哪些功能需求與非功能需求？
2. 重新調整類別圖，以滿足新的需求。
3. 活動圖。
4. 有哪些程式需要修改？請列出工作項目（Issues）。


### Mobile Tickets Case Study ###

本公司今年度主要目標是發展行動購票服務，
舉凡演唱會、音樂會及各種表演活動，
顧客都可以透過手機即時瀏覽最新的訊息，
並利用信用卡直接刷卡訂票。

（預計可涵蓋內容）

1. 從市場調查、訪談及問卷瞭解需求。
2. 由專案團隊負責撰寫提案報告（proposal）。
3. 瞭解並使用 MVC 開發框架。
4. 訂定里程碑（milestone）。
5. 使用 UML 製作系統分析與設計文件。
6. 使用 Wireframe Tools 描繪系統雛型。
7. 考慮所採用的開發技術等。（SEO, Web Services, Cloud, ...）
8. 思考如何佈署？未來如何擴展（scale-out）？

[astah]: http://astah.net/ "Astah"
