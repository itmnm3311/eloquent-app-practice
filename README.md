# eloquent-app-practice

## 概要
COACHTECH 教材 Tutorial 9-4「Eloquent ORM ハンズオン演習」で作成した成果物です。
LaravelのEloquent ORMを使って、投稿データの作成・取得・更新・削除（CRUD操作）ができる投稿管理アプリを作成しました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- Eloquent ORM
- MySQL
-Docker
-Laravel Sail

## 学んだこと
- モデルの $fillable や $casts を使って、データの一括代入や属性の型変換を設定する方法
- Eloquent ORMを使ったデータの作成・取得・更新・削除（CRUD操作）
- findOrFail() を使って、指定したIDのデータを取得し、存在しない場合に404エラーを返す方法

## 動作確認
1.プロジェクトのディレクトリに移動する
2.Dockerコンテナを起動する
./vendor/bin/sail up -d
3.ブラウザで以下のURLにアクセスする
http://localhost/posts
投稿一覧の表示、新規投稿、投稿内容の更新、削除ができることを確認します。
