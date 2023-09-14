## setup用のコマンド
- READMEに書いてあるものだと、うまく動作しないので、ここに書いています。
```bash
$ cd webapp/sql
$ curl -L -O https://github.com/catatsuy/private-isu/releases/download/img/dump.sql.bz2
$ bunzip2 dump.sql.bz2
$ cd ../../
$ docker compose -f webapp/docker-compose.yml up
```
