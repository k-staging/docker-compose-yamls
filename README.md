### 使い方  
忘れやすい自分のために, docker-compose を使ってコンテナ起動する方法を書いておく  

```
[コンテナ作成/起動]
$ docker-compose up -d

[コンテナ停止/削除]
$ docker-compose down

[コンテナ一覧確認]
$ docker-compose ps

[コンテナのログ確認]
$ docker-compose logs
```

### コンテナに bash でログインしたい場合  
以下のコマンドで bash ログインする事ができる  

```
[redis のコンテナにログインしたい場合]
$ docker-compose exec redis bash

[mysql のコンテナにログインしたい場合]
$ docker-compose exec mysql bash
```
