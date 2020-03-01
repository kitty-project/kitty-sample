# kitty-sample
## Install Kitty
```shell
$ git clone https://github.com/kitty-project/kitty
$ cd kitty
$ git checkout develop
$ ./mvnw install
```
## Run sample application
```shell
$ git clone https://github.com/kitty-project/kitty-sample
$ cd kitty-sample
$ ./mvnw package
$ java -jar ./target/kitty-sample-0.0.1-SNAPSHOT.jar
```
## Open browser and hit the URLs:
```
http://localhost:7001/api/users/1
http://localhost:7001/greetings
http://localhost:7001/api/hi
http://localhost:7001/about
```