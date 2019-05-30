#### How to run

```SHELL
git clone https://github.com/souhaiebtar/thingsboard_cassandra
cd thingsboard_cassandra
docker-compose up -d
```


copy mqttserver certificate inside container

```SHELL
docker cp certificate/mqttserver.jks thingsboard_cassandra_tb_1:/etc/thingsboard/conf/mqttserver.jks
```
=======
N.B: *it will take some time depending on your PC, just wait for some time*