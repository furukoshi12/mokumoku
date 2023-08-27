# README

## 環境構築
```
$ bundle install --without=production
$ bin/rails db:setup
$ yarn install
$ bin/webpack
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください
選択した事業側の課題
サービス登録者数の内、男性60%に対して、女性は40%。一方で、サービス内のもくもく会に参加した人の比率は、男性90%：女性10%と大きな差が出ています。もっと女性が使いやすいようなサービス設計にする必要があるのではないか？

提案内容
女性がオフラインのイベントに参加する際、気になるのがその会や主催者が信頼できるかという面が大きいと思うのでもくもく会の主催側と参加側で相互に評価する仕組みを作りそのユーザーが信頼できるかを一目で分かるようにする。
またフォロー機能を実装しフォローしているユーザー一覧からそのユーザー詳細に飛べるようにする。

実装方針
実施済みのもくもく会に星評価を付けれるようにする。
星評価の平均をユーザー名の横に表示する。
フォロー機能を追加する。
フォローユーザー一覧とユーザー詳細を追加する。
ユーザー詳細には主催しているもくもく会の一覧を表示する。
