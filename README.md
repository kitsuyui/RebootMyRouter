# これはなに

私の家にある家庭用のルータ
 [WRC-1467GHBK-A](http://www2.elecom.co.jp/products/WRC-1467GHBK-A.html)
をコマンドラインで再起動するためのスクリプトです。

~~本当は業務用ルータがほしいです。~~

# 使い方

ルータを再起動します

```console
$ ./bin/reboot-router
```

## セットアップ方法

```console
$ git clone git@github.com:kitsuyui/RebootMyRouter.git
$ cd RebootMyRouter
$ cp .env.sample .env
```

`.env` の中身を自分の使用環境にあわせて書き換えておきます。

```
export BASIC_AUTH_USERNAME='xxxxxxxxxxxxxxxxxx'
export BASIC_AUTH_PASSWORD='xxxxxxxxxxxxxxxxxx'
export ROUTER_HOST='192.168.0.0'
```

# License

[CC0-1.0](LICENSE)
