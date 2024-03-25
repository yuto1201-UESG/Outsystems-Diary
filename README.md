# Outsystems-Diary

##  Outsystemsで日記アプリを作る！


ローコードツールで簡単な日記アプリを作ってみた。
今回はモバイル用のアプリを作成。いくつかプラグインを追加した。  
作成アプリ → Yuto_Diary.oap  

### 環境
*  Macbook air(M1)
*  MacOS 14.4
*  Outsystems(Version 11.54.51)



作成したアプリスクリーンは、日記を閲覧するスクリーンと日記を編集する画面の2つ。


<日記閲覧スクリーン>   
この画面では日記を日付ごとに閲覧できる。
上部の箇所で日付を選択し、見たい日記のを閲覧。  
左上に感情情報、右上に日付を表示。  
中央には画像3枚を横並びに表示し、その下の緑の欄に日記を表示。

<img src="https://github.com/yuto1201-UESG/Outsystems-Diary/assets/163832489/1254eda6-d95a-48de-960c-9ec02a311f38" width="250">  


.

  
<日記編集画面>  
日記画面の右下のボタンから編集ボタンを出し、日記編集画面に移動できる。
編集画面では上から順に、その日の感情、画像3枚、テキスト(日記)を編集できる。
感情については、５つのうち１つのみ選択可能。

 
<img src="https://github.com/yuto1201-UESG/Outsystems-Diary/assets/163832489/959d4971-349a-4525-be9f-b4785fea865e" width="250">
<img src="https://github.com/yuto1201-UESG/Outsystems-Diary/assets/163832489/55507426-c1e9-4a5d-91a7-217209a8ce15" width="250">


.

<使用プラグイン>
1.  Camera Plugin (デバイスの写真フォルダへのアクセス)
2.  Horizontal Date Picker (1週間の日付表示と日付選択)
3.  Lightbox Image (画像の拡大表示)

-Horizontal Date Picker-  
<img src="https://github.com/yuto1201-UESG/Outsystems-Diary/assets/163832489/c82a1838-9b10-47b6-9d13-bacc576988d7" width="250">

-Lightbox Image-  
<img src="https://github.com/yuto1201-UESG/Outsystems-Diary/assets/163832489/21923cd2-5d3c-4dff-98ee-9cb73db921ce" width="200">



ネット上に情報が少なくて、困る場面が多かった。データベースでのデータのやり取りや、画像の表示が思い通りにできなかったり、、  
改善点は多々あるが1週間程度で形にできた。











