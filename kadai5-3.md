## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
  https://zipcloud.ibsnet.co.jp/api/search
　郵便番号を入力すると住所を検索してくれる
* リクエストとレスポンスのフォーマット
  https://zipcloud.ibsnet.co.jp/api/search?zipcode=1000001
  JSON
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
  wttr.in
  https://wttr.in
* エンドポイントと機能
  https://wttr.in/{都市名}?format=3
    都市を指定すると天気を返してくれる
* リクエストとレスポンスのフォーマット
  https://wttr.in/Tokyo?format=3
　テキストベース
### Q3-3. 感想
* 今回の課題で苦労したこと
  APIを呼び出して実際に表示させるのが難しかった
* 演習を通して理解できたこと
  JSによる外部APIの実行方法
* Web APIの利便性や課題など
  外部の情報を拾ってきて表示してくれるから、できることの幅が増えた。
