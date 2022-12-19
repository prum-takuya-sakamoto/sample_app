# Ruby on Rails チュートリアルのサンプルアプリケーション

これは、次の教材で作られたサンプルアプリケーションです。
[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)
（第6版）
[Michael Hartl](https://www.michaelhartl.com/) 著

## ライセンス

[Ruby on Rails チュートリアル](https://railstutorial.jp/)内にある
ソースコードはMITライセンスとBeerwareライセンスのもとで公開されています。
詳細は [LICENSE.md](LICENSE.md) をご覧ください。

## 本番環境のURL
https://fierce-stream-22445.herokuapp.com/

## ログイン情報
アプリへの登録はせず、ログインだけを行いたい場合は以下の情報にてログインしてください。

**Email**

example@railstutorial.org

**Password**

foobar

## 使い方・ローカル環境での起動方法

このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。
その後、次のコマンドで必要になる RubyGems をインストールします。

```
$ gem install bundler -v 2.2.17
$ bundle _2.2.17_ config set --local without 'production'
$ bundle _2.2.17_ install
```

その後、データベースへのマイグレーションを実行します。

```
$ rails db:migrate
```

最後に、テストを実行してうまく動いているかどうか確認してください。

```
$ rails test
```

テストが無事に通ったら、Railsサーバーを立ち上げる準備が整っているはずです。

```
$ rails server
```

詳しくは、[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)
を参考にしてください。

## 今回の勉強したことのメモ
[Ruby on Rails の勉強メモ](https://scrapbox.io/takuyasakamoto-73997658/Ruby_on_Rails_%E3%81%AE%E5%8B%89%E5%BC%B7%E3%83%A1%E3%83%A2)
