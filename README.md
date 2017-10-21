# Premier App

## bundle install
以下のコマンドで Gemfile に記述のある Gem をインストールする

```
$ bundle install --path vendor/bundle --without staging production --jobs=4
```

## アプリの起動
```
$ rails s
```

http://localhost:3000 へアクセス
