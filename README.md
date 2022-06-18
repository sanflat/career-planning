# Career Plannign App

# Use Tech
* [Docker](https://www.docker.com/)
* [Gradle](https://docs.gradle.org)
* [Java](https://www.oracle.com/jp/java/)
* [Spring Boot](https://spring.io/projects/spring-boot)
* [Thymeleaf](https://docs.spring.io/spring-boot/docs/2.6.3/reference/htmlsingle/#boot-features-spring-mvc-template-engines)
* [Bootstrap 5](https://getbootstrap.jp)
* [MySQL](https://www.mysql.com/jp/)
* [MyBatis Framework](https://mybatis.org/spring-boot-starter/mybatis-spring-boot-autoconfigure/)

# Environment Building
## Clone
### remote url
```
// https
$ https://github.com/sanflat/career-planning.git

// ssh
$ git@github.com:sanflat/career-planning.git

// GitHub CLI
$ gh repo clone sanflat/career-planning
```

##Get Started
###ルートディレクトリから、docker-compose.ymlファイルのディレクトリに移動
```
$ cd docker/
```
###docker-composeの下記コマンドを実行し、ビルドが成功しDockerImageが作成される事を確認する
```
$ docker-compose build
```
###docker-composeの下記コマンドを実行し、コンテナの起動を確認する
```
$ docker-compose up
```

# command list
Docker コンテナのDBに入る
```
$ docker exec -it docker-db-1 bash
$ mysql -u user -ppassword hackers_log_db
```

# document list
* [アイデア:ラフ](https://miro.com/app/board/uXjVOt6QoLE=/)
