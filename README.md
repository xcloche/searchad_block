# searchad_block
Adblockでは消せない検索広告を消すGoogle Chromeの拡張機能です。  
Google検索したときリストの上の方に太字で出る<b>広告</b>の表示つきの検索結果が見えなくなります。  
下のほうに表示される<b>広告</b>つき検索結果、および画像検索した際にたまに上段に出る広告も非表示にします。  
原理は単純で、指定したドメイン内の指定した```div class```や```div id```の要素をCSSで非表示にしています。（今回はGoogleの検索広告関連のもの）

### Usage
1. ダウンロード  
緑色のCodeボタンから Download ZIP するか、  
ターミナルで  
```git clone https://github.com/xcloche/searchad_block.git```  
してコードの入ったディレクトリを準備してください。

2. Chromeへ拡張機能を登録  
Chromeの拡張機能管理ページ  
<a href=chrome://extensions>chrome://extensions</a>  
で、画面上の「パッケージ化されていない拡張機能を読み込む」ボタンを押して、1.で準備したディレクトリ（.jsonが入ってるやつ）を指定してください。
    
3. 消えます

### オプション  
google/style.css の中の最後のコメントアウトを外すと、検索結果からGoogleがおせっかいで探してきてくれた地図とかTwitterで見つけてきたのとかも消えます

### 消したいのを探そう
Adblockが忖度している広告や、実際邪魔だけど消したい広告でないものを、CSSのclass指定非表示でドンドン消していきましょう

### 更新履歴
2021/05/19 Google検索結果+α消えるやつ公開
