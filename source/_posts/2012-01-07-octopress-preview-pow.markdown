---
layout: post
title: OctopressのpreviewをPowでやると便利ですよという話
date: 2012-01-07 16:12
comments: true
categories: octopress
---

<a href="http://www.flickr.com/photos/marutanm/6597268041/" title="2 by marutanm, on Flickr"><img src="http://farm8.staticflickr.com/7018/6597268041_14c0e61b4b_m.jpg" width="240" height="159" alt="2" class="left"></a>
地味にめんどうなんですよね、Octopressでローカルプレビューするの。

普通にやるとすると```rake generate```でmarkdownを変換して、```rake preview```でローカルでjekyllを起動してブラウザで確認といった流れ。
エントリ投稿毎に再構築とか、なんかウェブログという言葉がメジャーになり始めた頃を思いましますね。
さておき、少しの変更のたびにコマンド2発、エディタとターミナルとブラウザをいったりきたりする必要があります。
そこで、やっぱり[Pow](http://pow.cx)ですよ。
```rake preview```せずに```public/index.html```をブラウザで確認できるようになります。
また、```rake watch```を使えば編集中のファイルを保存した時点でエントリを再生成してくれるので、```rake generate```が不要になります。

なんですが、[公式ドキュメントにも書いてる](http://octopress.org/docs/blogging/)ので自力でOctopressを使えるひとなら言わずもがなですよね・・・

