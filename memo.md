### やったこと

* commentとuncomment

* MipMapとは

**commentとuncomment**

command+/で変更可

**使用前**

<img src="https://github.com/ryoya-cre8or/TIL_day3/blob/main/%E3%82%B7%E3%83%A7%E3%83%BC%E3%83%88%E3%82%AB%E3%83%83%E3%83%88%E3%82%AD%E3%83%BC%E5%89%8D.png" width="600px"/>

**使用後**

<img src="https://github.com/ryoya-cre8or/TIL_day3/blob/main/%E3%82%B7%E3%83%A7%E3%83%BC%E3%83%88%E3%82%AB%E3%83%83%E3%83%88%E3%82%AD%E3%83%BC%E5%BE%8C.png" width="600px"/>

※ Remember

pubspec.yamlでは//(ダブルスラッシュ)でコメントにできない

**Every indents two spaces**

<img src="https://github.com/ryoya-cre8or/TIL_day3/blob/main/assets%E3%81%AE%E3%82%B9%E3%82%99%E3%83%AC.png" width="600px"/>

↑これではassetsがFlutterのchildrenであることを認識できない(Flutterに対して3spacesのindent)

**MipMapとは**

[MipMapって何？](https://qiita.com/dgtanaka/items/2ec0fd88236daa5c3cc7)

[動画も参照](https://www.youtube.com/watch?v=knqdwREIM2U)

要は近くの画質は高く、遠くの画質は小さくすることで描画負荷を軽減する手法

→アプリのicon作りで使う

<img src="https://github.com/ryoya-cre8or/TIL_day3/blob/main/icon%E3%81%AE%E8%A8%AD%E5%AE%9A.png" width="500px">

**Android**

<img src="https://github.com/ryoya-cre8or/TIL_day3/blob/main/icons.Android.gif" width="500px"/>

Androidの場合丸型としてiconが表示されることもあるからAssetimagesで調整が必要

※最新版Flutterでは表示されないこともある(僕のAndroid Studioは表示されない)

この場合Android moduleをもう一つ開くことでAssetimagesは表示される

<img src="https://github.com/ryoya-cre8or/TIL_day3/blob/main/Image.assets.gif" width="500px"/>

<img src="https://github.com/ryoya-cre8or/TIL_day3/blob/main/icons.Android.gif" width="500px"/>


**iOS**

<img src="https://github.com/ryoya-cre8or/TIL_day3/blob/main/icons.iOS.gif" width="500px"/>
