# private-isu

「[ISUCON](https://isucon.net)」は、LINE株式会社の商標または登録商標です。

## OS

Ubuntu 22.04

## MySQL
### 設定
1. `webapp/etc/mysql/conf.d/my.cnf` に定義する。

### pt-query-digest
1. ローカル OS に `$ brew install percona-toolkit` などで percona-toolkit をインストール
2. `$ pt-query-digest webapp/logs/mysql/mysql-slow.log`
