# Insert AmazonPoints in the Wishlist

AmazonのWishlistに入っているKindle本のAmazonポイントを表示させる拡張

ポイント表示の前に区切りのスラッシュを入れる版(個人的には開発者モードからの利用で十分なので、パッケージ化の予定はありません)

# Version
0.2.1.1

## Install
### Microsoft Edge
1. git cloneやZIP Downloadを行いファイルを入手
1. 拡張機能の管理ページ(edge://extensions/)の左下にある開発者モードをオンにして、「展開して読み込み」をクリック
1. 入手したフォルダを指定して選択をクリック

### Chrome
1. git cloneやZIP Downloadを行いファイルを入手
1. Chrome拡張機能画面の上部のデベロッパーモードにチェックを入れて、「パッケージ化されてない拡張機能を読み込む」をクリック
1. 入手したフォルダを指定して選択をクリック

### Firefox
Firefoxをメインで使っているわけではないので不明  
ただ、WebExtensionsAPIで開発しているため、以下の通りに動かせばいけるのではないかと思います(未確認)  
https://developer.mozilla.org/ja/docs/Mozilla/Add-ons/WebExtensions/Porting_from_Google_Chrome

## Usage
1. インストール後オプション画面が開くので、保存をクリック
1. AmazonのWishlistのページを開いて少し待つとポイントが値段の隣に表示される

## Update History
0.2.1.1
区切りのためにポイント表示前にスラッシュを入れるように対応

0.2.1
bugfix

0.2.0
* AmazonのWishlistのurlが違うものができていたので対応ページに追加
* Wishlistのページ構成がページ移動から無限スクロールになっていたので対応
* いつの間にかFetchAPIが使えるようになっていたのでEnableに　デフォルトもFetchAPIに
* jQueryの新しいバージョンが出ていたので確認したところ、問題なく動作したので更新
* その他いくつかリファクタ

## License
Copyright (c) 2017 sytkm
Released under the MIT license
http://opensource.org/licenses/mit-license.php
