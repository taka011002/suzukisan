# suzukisan

## about
悩みを相談したい人と人の悩みを聞いてあげたい人をマッチングし、通話できるサービスです。

## architecture
![architecture](architecture.png)

## database
![db](db.png)

docker run \
  -d --restart=always \
  -e "SPRING_PROFILES_ACTIVE=prod" \
  -p 4000:4000 \
  prefix/imagename