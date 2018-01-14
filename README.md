# robosys2017 課題2 

1526089 花田百優

## 課題2の出題内容 

* ROSで何かを作る
  * 例（難しいものから）
    * 自分のロボットをROS化
    * LEDを光らせるノード
    * 講義のものを改造（ここまでが満点の可能性）
    * 講義のものをそのままGitHubにアップ
  * 注意
    * 課題1と同じくGitHubにプッシュ->Youtube->私まで電子メール
    * ライセンス、何をやったか分かるREADMEを書く
    * 得点の目安は課題1と同じ

## 私がやったこと

授業についていくのが必至過ぎたので、授業の内容をやりました。  
### ロボットシステム学2017第12回 (https://github.com/ryuichiueda/robosys2017/blob/master/12.md )
ROSを用いて数をカウントするプログラム。 
* 対象ファイル 
  * count.py 
    * rospy.Publisherを作って定期的にデータを投げる 
    * 実行動画:https://instagram.com/p/Bd4ECrQjkEj/
  * twice.py 
    * 2倍になった数字が端末に表示される
    * 実行動画:https://instagram.com/p/Bd4ESnZDb1T/ 
    * パブリッシャとサブスクライバを同居させる
    * 実行動画:https://instagram.com/p/Bd4EfrDjA6B/
    
### ロボットシステム学2017第13回 (https://github.com/ryuichiueda/robosys2017/blob/master/13.md )
ROSからウェブにデータを飛ばしてブラウザで閲覧する。 
* 対象ファイル 
  * index.html 
  * main.js 
  * webserver.py 
    * ROSからウェブにデータを飛ばす
    * 実行画像:https://instagram.com/p/Bd6tNQWDQib/ 
    * 最小限のHTMLを書く
    * 実行動画:https://instagram.com/p/Bd6tVIAjDaP/ 
    
## 動作環境　　
- Ubuntu (ver. 16.04)  
- Tera Term (ver. 4.86)　　
