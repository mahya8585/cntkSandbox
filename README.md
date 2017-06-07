# cntkSandbox
cntkのチュートリアルうごかしたり、なんか作って遊んだり、色々悩んだりするところ


## for Java

残念ながらCNTKライブラリはmavenリポジトリにないので手動登録します

```
install:install-file -Dfile=[パス]/cntk.jar -DgroupId=com.microsoft -DartifactId=cntk -Dversion=1.0 -Dpackaging=jar -DgeneratePom=true


<dependency>
   <groupId>com.microsoft</groupId>
   <artifactId>cntk</artifactId>
   <version>1.0</version>
</dependency>

```
