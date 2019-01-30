# Android Sunflower for DroidKaigi 2019

[DroidKaigi 2019](https://droidkaigi.jp/2019/)のセッション「[EspressoのテストをAndroidの最新トレンドに対応させよう](https://droidkaigi.jp/2019/timetable/70791)」のサンプルコードです。

本リポジトリは、
GoogleがAndroid Jetpackのサンプルアプリとして開発している[Android Sunflower](https://github.com/googlesamples/android-sunflower)をフォークしたものです。

Android Sunflower付属の、オリジナルのREADMEは[README.orig.md](README.orig.md)を参照してください。


## 動作確認環境

- Android Studio 3.3
- 言語設定を日本語にしたAndroid 8.0が稼動する端末

# ブランチ

TBD

- master:  
  フォーク元のmasterブランチです。

## オリジナルのAndroid Sunflowerとの違い

- Android Studio 3.3でビルドできるように、ビルドスクリプトを修正しています。
- AndroidX Test関連のライブラリを依存関係に追加したり、バージョンを最新化しています。
- `app/src/androidTest`配下のテストコードを全て削除しています。
  代わりに、本セッションのサンプルコード(テストコード)を追加しています。
- オリジナルのREADME.mdのファイル名をREADME.orig.mdにリネームしています。

## ライセンス

Original Copyright 2018 Google, Inc. See [README.orig.md](README.orig.md) for details.

Modifications Copyright 2018-2019 TOYAMA Sumio &lt;jun.nama@gmail.com&gt;  

Licensed under the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

### Third Party Content

Select text used for describing the plants (in `plants.json`) are used from Wikipedia via CC BY-SA 3.0 US (license in `ASSETS_LICENSE`).
