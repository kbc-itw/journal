# 情報技術研究会　部誌
これは、**河原電子ビジネス専門学校 情報技術研究会**の部誌です。  
研究会のガイドラインや、活動記録などを記録しています。

**GitHub Pages**上で公開しています。  
https://kbc-itw.github.io/journal/


## 執筆に関して
各文章はMarkdownで記述し、HTMLやPDFへの変換には、[**GitBook**](https://github.com/GitbookIO/gitbook)を利用しています。  
GitBookを使う上での詳しい記法や設定に関しては、以下のURLを参照してください。  
https://toolchain.gitbook.com/

### 環境
Node.js v6.x 以上

### ビルド
リポジトリをcloneしたのち、まずはそのディレクトリに移動してから `npm install` を実行してください。  
その後、リポジトリ配下で以下のコマンドが実行できるようになります。

+ `npm run build`  
  Markdownファイルなどを元にHTMLファイルなどを生成します。  
  ただし、下記のserveコマンドでもビルドされるため、基本的にはこのコマンドを実行する必要はありません。
+ `npm run serve`  
  ビルドしたのちに、ローカルにHTTPサーバーを起動します。  
  コマンドラインに出力されるURLにアクセスすることで、実際の表示を確認することができます。  
  サーバー起動中はファイルの更新を検出して自動で再ビルドされます。
  
htmlなどは直接変更しないでください。  
mdファイルを更新した上で、上記のnpmスクリプトコマンドのいずれかを介してビルドしましょう。  

### デプロイ
GitHub Pagesでは、masterブランチの/docs配下を公開するように設定しています。  
変更内容をcommit+pushすると、公開されている内容が更新されます。


## 関連リンク
+ [情報技術研究会](http://kbckj.net)
+ [河原電子ビジネス専門学校](http://www.kawahara.ac.jp/kbc/)
+ [ITエンジニア科学科ブログ](http://www.kawahara.ac.jp/kbc/advanced_blog/)

太郎