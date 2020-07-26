## 勉強メモ

#### #centosにsshする

https://holidaynote.hatenablog.jp/entry/2018/04/21/224858

### #java11を入れる

はまりポイント:yumでリポジトリの情報が取れるくせにインストールできない

→/etc/resolv.confにDNSの情報がなく、名前解決ができなかった。

(このconfファイル、再起動時に書き換わるらしい)

おそらくyumのリポジトリ自体はipでやりとりしているが中身のリンクはhostnameなため。



