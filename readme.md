# Data Collection and Persistence

### Data Sources 

  - 使用TwitterAPI
  - 抓取社會影劇類
  - 下#oscarssowhite查詢
  

### Data Format(JSON）

* [contributors] - 使用者物件的集合，象徵幫助Tweet的人，代表官方tweet創辦人
* [truncated] - tweet是否被裁切掉，超過140字會被切掉
* [text] - 文字內容
* [is_quote_status] - 是否被引用的狀態
* [in_reply_to_status_id] -  若這篇Tweet為回覆別人的Tweet才會顯示被回覆的Tweet的ID（以整數表示）
* [id] - 這篇Tweet的ID（以整數表示），數字會大於53bit造成有些程式語言難以解譯 
* [favorite_count] - 這篇Tweet有多少個喜歡
* [retweeted] - 這篇Tweet是否有被其他Twitter使用者轉發
* [coordinates] - 這篇Tweet的發文座標
......
