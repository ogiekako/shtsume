#  shtsume
##  Featured
shtsume(**sh**ell **tsume**shogi solver)は以下の特徴を持つ詰将棋解図プログラムです。  
* コマンドライン（shell)上で詰将棋解図ができます。  
* USIプロトコルに準拠しており、詰将棋エンジンとして使用する事ができます。   
* 探索レベルの設定により、特定局面の詰み/不詰判定から詰将棋作品の作意推定まで可能です。  
* 探索LOGにより詰め手順中の玉方変化時の詰手数、駒余りの有無を確認することができます。

詰将棋作品の鑑賞や新作の検証に利用できるToolになれば幸いです。   
インストールおよび使用法は[wiki](https://github.com/hkijin/shtsume/wiki)を参照してください。  

##  Requirement  
動作確認OS  
* macOS (INTEL, M1) 
* Windows(+minGW w64 環境）  

##  Goal
shtsumeの開発は以下を目標としています。  
* 高効率　　少ない探索量で解を導きます。    
* 省メモリ　難解な作品であっても少ないメモリで解を導きます。  
* 高精度　　完全作であれば作意解（正解）を出力する。  
* 高速　　　プログラムの高速化を図っていく。 

##  Achievement
v1.1.1   2023.11.30    
* 詰探索　証明駒の再見直し。（前リリースで一部の作品が詰ましにくくなったため）  

v1.1.0   2023.10.31  
* コマンドライン　詰探索開始前に局面の合法性チェックを導入。  
* 詰探索　読み筋表示に使用しない探索LOGの書き込み・ゼロクリアを削除。約10%高速化。  
* 詰探索　証明駒の効率化。  

v1.0.15  2023.9.30  
* 詰将棋作品を先後反転して解図を行った場合、空き王手の候補手が生成できない問題を再修正。  

v1.0.10　　2023.1.28  
* 詰将棋作品を先後反転して解図を行った場合、空き王手の候補手が生成できない問題を修正。  
* 解図速度をわずかに改善。  

v1.0.5　　2022.12. 8  
* 連続で詰将棋の解図を行った場合、探索レポートの一部に不具合が発生する問題を修正。  
  
v1.0.3　　2022.11.18  
* 千日手不詰めの解図速度改善  
* 駒を余す不完全作への解答表示変更。 
 
v1.0.0　　2022.10.26  
* ファーストリリース  　　

