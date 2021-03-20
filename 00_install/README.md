# Visual Studio Code Install 

## 手順
- 以下のサイトから`.dep`をダウンロードする。 
  - https://code.visualstudio.com/Download

- 以下のコマンドでダウンロードした`.dep`をインストールする
    - `*.deb` は Tab補完できなかった。
    - `*.deb` に実行権を付与する必要性は不明(とりあえずつけた)

```sell
$ sudo apt install ./code_1.54.3-1615806378_amd64.deb
```

## 注意
- snap でのInstall だと、`半角/全角`キーで日本語入力への切換ができない
  - [Linux Mint 20.1にSnapでインストールしたVisual Studio Codeで日本語入力できない件](https://haiju.hatenablog.com/entry/2021/02/17/170220)


## 参考
- この手順(英語)を実施しただけ
  - [Debian and Ubuntu based distributions](https://code.visualstudio.com/docs/setup/linux)

以上