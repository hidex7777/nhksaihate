# nhksaihate

NHKラジオ第一「最果てラジオ2017」録音スクリプト

※2017年12月30日（土）17時04分までにのみ実行できる

## 必須要件

- Woindows Vista以降（テストは7でしか行っていません）

## 使い方

VLCメディアプレーヤーがインストールされていることが前提。

nhksaihate.ps1ファイルをメモ帳などのテキストエディタで開き、

```
$vlcexe = 'C:\Program Files\VideoLAN\VLC\vlc.exe'
```

この部分を、自分の環境に書き換える。64bitOSでCドライブにVLCをインストールしていれば、このままでOKだと思う。

同様に、

```
$destdir = 'E:\music\nhk-bungei\'
```

の部分を、音声ファイルを保存したいディレクトリ名に変える。あらかじめフォルダ（上の例だとnhk-bungeiというフォルダ）を作っておく。

nhkbungei.batファイルをダブルクリックすると、録音が予約される（コマンドプロンプトの黒いウィンドウが出るので、最小化しておいてかまわない）。
