# MeiCB

<img src="https://github.com/takashicompany/meicb/blob/master/images/01.jpg?raw=true" width="600px"/>

MeiCB(メイシービー)は名刺サイズのキーボード基板です。  
名刺として使えますし、キースイッチやMCUを搭載することで簡易的なマクロパッドとしても利用できます。  
Kicadデーターを公開予定ですので、ご自身のプロフィールやアイコン画像を載せたMeiCBをつくることも可能です。  

(my_meishiから名前を変更しました。)

## 機能の対応状況

### Rev2(my_meishi)

一部の機能は、まだファームウェアの調査中だったり、基板側に拡張が必要なケースがあります。

|機能|対応|詳細|
|:--|:--|:--|
|OLED|？|現在調査中。|
|LED|✗|基板側で追加の実装が必要になる想定。|
|VIA|？|現在調査中。|

## 組み立てに必要な部品

|部品名|個数|備考|
|:--|:--|:--|
|[XIAO RP2040](https://akizukidenshi.com/catalog/g/gM-17044/)|1||
|キースイッチ|4個|取り付けは[Cherry MX互換キースイッチ](https://shop.yushakobo.jp/collections/all-switches/cherry-mx-%E4%BA%92%E6%8F%9B-%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81)と[Kailh Choc v1互換キースイッチ](https://shop.yushakobo.jp/collections/all-switches/kailh-choc-v1%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81)に対応|
|キーキャップ|4個||
|[ゴム足シール](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800ur-01-6)|4個||

## 組み立て方

### 1. 基板の表側にXIAO RP2040を取り付ける

基板の表側右上の箇所にXIAO RP2040を取り付けます。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_1977.jpg?raw=true" width="600px"/>

XIAO RP2040とピンをはんだ付けします。  
ピンの足がXIAO RP2040の平らな面側に来るようにピンを差しハンダ付けを行います。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_1981.jpg?raw=true" width="600px"/>

XIAO RP2040をMeiCB基板に差します。  
USBの口が外側を向くようにしてください。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_1982.jpg?raw=true" width="600px"/>

表面から見たときに、このようになっていれば問題ありません。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_1983.jpg?raw=true" width="600px"/>

基板とピンをハンダ付けする前にピンをニッパーなどで短く切っておくとハンダ付けがしやすくなり且つ仕上がりが綺麗になります。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_1985.jpg?raw=true" width="600px"/>

全てのピンをハンダ付けしたら完了です。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_1986.jpg?raw=true" width="600px"/>

### 2. キースイッチを取り付ける

キースイッチを取り付けます。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_1995.jpg?raw=true" width="600px"/>

キースイッチをMeiCB基板に配置します。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_1996.jpg?raw=true" width="600px"/>

キースイッチをマスキングテープなどで固定すると、以降の作業をスムーズに進められます。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_1999.jpg?raw=true" width="600px"/>

MeiCB基板を裏返したときに、キースイッチの足が出ていることを確認します。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_2002.jpg?raw=true" width="600px"/>

MeiCB基板とキースイッチをハンダ付けします。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_2003.jpg?raw=true" width="600px"/>

キーキャップを取り付けます。  
<img src="https://github.com/takashicompany/meicb/blob/master/images/build/IMG_2008.jpg?raw=true" width="600px"/>
