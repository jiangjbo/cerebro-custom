# 使用v0.8.4做的定制化

# jar修改

## org.xerial.sqlite-jdbc-3.20.0.jar
META-INF/services/java.sql.Driver
修改为mysql驱动
com.mysql.jdbc.Driver

## cerebro.cerebro-0.7.2-launcher.jar
META-INF/MANIFEST.MF
修改classpath，添加com.mysql.mysql-connector-java-5.1.39.jar

# 配置修改
## conf\evolutions\default\1.sql

## conf\application.conf

## conf\reference.conf

