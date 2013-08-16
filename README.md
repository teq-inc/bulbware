## Bulbware

Bulbwareは、Webアプリケーション開発用のライブラリ／フレームワークです。

Bulbとは球根のことです。水耕栽培でも育つ球根植物は、植えて水をやるだけで花を咲かせます。そんな少しの手間で、Webアプリケーションが作れたらいいな、と考えました。

球根植物を植えるだけでは美しい花壇は作れないように、より高度なアプリケーションにするためには、それなりの手間が必要にはなるでしょう。そのためにユーザーインタフェースの開発に集中することができるライブラリ／フレームワークとなっています。

## 特徴

### サーバープログラムは、GAE/Pythonで開発

GAE(Google App Engine)のため、サーバー設置の面倒がありません。

### データモデルとAPIを用意

データモデルと操作用のAPIが構築されているので、開発したいアプリケーションに応じて選択するだけです。

### Backbone.jsとRequireJSによるライブラリ

APIの呼び出しはBackbone.jsのModelを使ったライブラリが、また基本的な表示はViewのライブラリがあります。
これらは、RequireJSでモジュール化してあるので、使いたいものを選んで使用できます。

### テンプレートエンジンとしてSNBinderを使用

SNBinderは、テンプレート側に処理構造がないので、テンプレートがシンプルになります。
複雑なテンプレート展開はJavaScriptで記述するため、処理の記述が分散しません。


## ライセンス

MIT License
