# Brython_OSjs
---
◆説明
[OS.js](http://os.js.org/)で使用可能なアプリケーションです。
今回は、公式の手順にて、作成を行いました。

[インストール方法](http://os.js.org/doc/manuals/man-package-manager.html)は、公式サイトを参照し、実行してください。
```
# src/packagesへ、クローンまたはダウンロード
$ git clone --recursive https://github.com/jack-low/Brython_OSjs.git

# リポジトリリストに追加
grunt config:add-repository:Brython_OSjs

# なお、リストからリポジトリを削除する場合
grunt config:remove-repository:Brython_OSjs

# マニフェストのアップデート
grunt manifest
```

◆パッケージの有効化と無効化

```
# 有効にする
grunt packages:enable:Brython_OSjs

# 無効にする
grunt packages:disable:Brython_OSjs

# マニフェストのアップデート
grunt manifest
```


