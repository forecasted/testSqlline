# testSqlline
use sqlline to connect clickhouse via jdbc.

# usage

## package

* mvn clean package
* cp testSqlline-1.0.0-SNAPSHOT-with-libs-dev.tar.gz to somewhere else. 


## run

* tar xvf testSqlline-1.0.0-SNAPSHOT-with-libs-dev.tar.gz
* cd testSqlline-1.0.0-SNAPSHOT
* java -cp testSqlline-1.0.0-SNAPSHOT.jar:lib/* sqlline.SqlLine -d ru.yandex.clickhouse.ClickHouseDriver


sqlline version 1.3.0
sqlline> !connect jdbc:clickhouse://ip:8123/database username password


