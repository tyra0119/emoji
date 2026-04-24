emoji.html
絵文字を表示、コピーするページ


https://tyra.jp/di/api/regist_popular
クライアントでコピーした内容をサーバー側で保存する処理
DB:SQLite3
/var/lib/stamp_popular/stamp_popular.db

内容の確認方法
sqlite3 /var/lib/stamp_popular/stamp_popular.db \
  "SELECT * FROM stamp_popular ORDER BY id DESC LIMIT 20;"




