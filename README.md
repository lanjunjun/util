# util

查询mysql已支持的存储引擎
show engines;
查询mysql当前默认的存储引擎:
show variables like '%storage_engine%';
查询某个表目前用的存储引擎
show create table 表名;
查询慢查询是否开启
查询多长时间会放到慢查询语句
show VARIABLES like 'slow_query_log';
show VARIABLES like 'long_query_time';

