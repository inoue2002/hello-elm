- elm 入門リポジトリ
  - https://guide.elm-lang.jp/

```
elm reactor
```

```
# ブラウザで開くことができるindex.htmlファイルを作成します。
elm make src/Main.elm

# 自前のHTMLドキュメントに埋め込むための最適化されたJSファイルを作成します。
elm make src/Main.elm --optimize --output=elm.js
```
