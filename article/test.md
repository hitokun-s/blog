クライアントサイドMVCを行う静的サイトの作成
====

###必要な機能###
- markdown->html変換器
- markdownとアプリケーション（html）の混在する記事を作成する仕組み
- 各記事URLはURLパスで識別する必要があるが、トップレベルにいるMVCマネージャとどう連携させるのか？  
  （MVCマネージャ：いろんなパーツを寄せあつめて最終的なページを作るjs）

###決めごと###
- 各記事のURL形式

###調べごと###
- markdownでアンカーは実現できる？

### markdown->html変換器 ###

StackOverFlowで使われている、PageDownを使ってみる。  
[https://code.google.com/p/pagedown/wiki/PageDown](https://code.google.com/p/pagedown/wiki/PageDown)