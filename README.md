# plusコマンド
ロボットシステム学2023

![test](https://github.com/tsubokuraryosuke/robosys2023/actions/workflows/test.yml/badge.svg)

## プログラムの目的　　
* 1から入力した数字までのすべての数字を足し合わせた結果の値を出力する。  

## インストール方法  
```
$ git clone https://github.com/tsubokuraryosuke/robosys2023 
$ cd robosys2023  
$ chmod +x plus
```  
`chmod +x plus`を行わないと実行例のように入力しても動きません。  
  
## 実行例  
```
$ seq 10 | ./plus  
55
```
1~10までの足し算の結果を出力します。  


## 必要なソフトウェア
* Python　　  
　　テスト済み: 3.7~3.10  

## テスト環境
* Ubuntu 20.04.6 LTS  

## ライセンス
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．  
[ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)  
© 2023　Tsubokura Ryosuke
