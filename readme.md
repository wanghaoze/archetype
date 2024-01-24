# 从原型创建一个应用骨架

- cola举例

1. 下载仓库
```shell
git clone https://github.com/alibaba/COLA.git
```
2. 安装原型
```shell
cd ./COLA/cola-archetypes/cola-archetype-service
mvn install
cd ../cola-archetype-web
mvn install
```
3. 新建应用
```shell
# 进入一个有pom管理的仓库
cd archetype
mvn archetype:generate -DgroupId=org.marsempire -DartifactId=demo-wb -Dversion=1.0.0-SNAPSHOT -Dpackage=org.marsempire -DarchetypeArtifactId=cola-framework-archetype-web -DarchetypeGroupId=com.alibaba.cola -DarchetypeVersion=4.4.0-SNAPSHOT
```

