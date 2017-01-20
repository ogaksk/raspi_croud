# raspi_croud
ウェブサイトから扇風機を回すためのシステムプロトタイプ

## Description  
特定のウェブサイト(<http://monougokasu.ogaksk.org>)からトリガーをwebsocketにてリアルタイム受信し、RaspberryPIで受信する。  
Node.jsで実装

## Demo  
画像を用意

## Usage
1. raspberryPIサイド起動
1-1. cd ~/project_root
1-2. node app.js

2. raspberryPIがbindするページにブラウザでアクセス。socket.IOがリモートサーバーとコネクションされる。

3. リモートサーバーの提供するウェブサイト(<http://monougokasu.ogaksk.org>)にアクセス。
