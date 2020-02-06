# robosys.kadai1


## 概要
デバイスドライバを用いてLEDを点灯させます。
## 動作デモ
https://youtu.be/AhocK_OZS0w 

## 動作環境、使用したもの
Raspberry Pi 3 Model B+ 
Raspbian
LED
抵抗：300[Ω]

## 導入
$git clone https://github.com/tomoya-kawasaki/Robosys.kadai1.git

## 使い方
1．LEDのアノード側をRaspberryPiの25番ピン、反対側を39番ピン(GND)に、適宜抵抗を挟むように接続します。

2．$sh make.sh を実行します。コンパイルからドライバのインストールまでをまとめて行います。

3．$sh led1.sh でLED点灯、$sh led0 でLED消灯を行うことが出来ます。

4．使用後は$clean.sh を実行することでアンインストールします。

## ライセンス
このソースコードはGNUライセンスで提供されています。LICENCEをお読みください。

## 作者
河崎 智哉
