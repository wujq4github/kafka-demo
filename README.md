## Kafka学习笔记


### 启动服务

进入kafka安装目录
> cd kafka_2.11-0.11.0.1

启动ZooKeeper服务器
> ./bin/zookeeper-server-start.sh ./config/zookeeper.properties

启动kafka服务器
> ./bin/kafka-server-start.sh ./config/server.properties


### 1.[Producer配置](doc/Producer配置.md)