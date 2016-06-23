#Kekule.jsシリーズ

---

## その1 導入

Kekule.jsを使っていくことになりましたので、できることを実演していきます。

まずはKekule.jsとは「なんぞや？」とか「何ができるん？」いうことを取り上げました。

### Kekule.jsってなんぞや？

いわゆる、化学分野専用のJavaScriptライブラリです。  
JavaScriptとはインターネットのWebページ(例えばこのページ)でなんか動かしたいときに利用されるプログラミング言語です。  
JavaScriptは今Web関係で最も熱いプログラミング言語ですから、Webに関わったことのある人でしたら聞いたことない人はいないでしょう。  
そのJavaScriptのライブラリということで、このライブラリを使えば化学関係のツールがWeb上に楽にできちゃいます。  


### Kekule.jsで何ができるん？

デモを見る限り、いろんなことができるみたいですね。  
化合物を見たり、描いたり、解析したり…、こんなことできるんだ。  
具体的にどこまで出来るのか、このシリーズを通して試していきたいので、乞うご期待というところでおねがいします。  


### とりあえず基本的なツールを作ってみよう！

とりあえず、化合物を描画できるツールを作ってみましょう。  

まずは<a href="http://partridgejiang.github.io/Kekule.js/download/files/kekule.js.zip">ここ</a>からzipファイルをダウンロードして展開・設置します。  

フォルダ構造はとりあえずこんな感じに。    

├ lib/  
│  └kekule.js/  <-- 先ほどダウンロードしたzipファイルを展開したフォルダ  
└ kekule_sample001.html   <-- 今回新たに作成したテキストファイル  

そしてkekule_sample001.htmlファイルの中身です。
```html:kekule_sample001.html
<html lang="ja">
<head>

  <title>このページのタイトル</title>
  <meta charset="utf8" /><!-- このページの文字コード指定 -->

  <!-- Kekule.jsからダウンロード・展開したkekule.jsフォルダはlibフォルダに入れています -->
  <!-- Kekule.jsスタイルの読み込み -->
  <link rel="stylesheet" type="text/css" href="lib/kekule.js/themes/default/kekule.css" />
  <!-- Kekule.jsライブラリの読み込み -->
  <script src="lib/kekule.js/kekule.js" />

</head>
<body>

  <!-- Kekuleエディタ生成 -->
  <div data-widget="Kekule.Editor.Composer"></div>

</body>
</html>
```

重要なのは9行目でダウンロードしたKekule.jsのスタイルの場所を指定していることと、11行目でライブラリの場所を指定していることです。
17行目でエディタウィジェットを生成する要素を書き込んでいますが、ここでは一番簡潔な方法としてdata-widget属性を使ってみました。


kekule_sample001.htmlをブラウザで開くとこんな感じにKekule.jsのエディタが表示されたでしょうか？

次回はエディタを詳しく見ていきたいと思います。

---

## その2 エディタ


---

## その3 ビューア


---

## その4 貼り付け素材


---

## 



