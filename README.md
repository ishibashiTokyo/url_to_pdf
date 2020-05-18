# Save Web page by Node.js

WebサイトをPDF、PNGで保存しスクラップや、差分チェックする用途で作成。

DOMでしゅんしゅんする系サイトはうまく取れないことがあるけど。。

## 使い方

クローンしたディレクトリで以下のコマンドを使い、パッケージの復元

``` bash
$ npm install
```

## main.js オプション

``` sh
$ node main.js --help

Usage: main.js [options]

	--help, -h
		Displays help information about this script
		'main.js -h' or 'main.js --help'

	--list, -l
		URLリストのファイルを指定
		"this.js -l url-list.txt" or "this.js --list=url-list.txt"

	--url, -u
		URLを単体で指定
		"this.js -u https://siteurl" or "this.js --url=https://siteurl"

	--auth, -a
		BASIC認証のUSERとPWを指定
		"this.js -b 'user:passwd'" or "this.js --basic='user:passwd'"
```


## image-diff.js

- 画像差分チェック
- 要ImageMagick
- 移設前移設後でサイトの出力が変わってないか画像ベースでチェックを行えるかテストしてみる。
