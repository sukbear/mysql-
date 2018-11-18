# mysql-
MySQL common knowledge

创建库
CREATE DATABASE IF NOT EXISTS table_name DEFAULT CHARSET utf8 COLLATE utf8_general_ci;

创建表（表中常用的字段）
CREATE TABLE IF NOT EXISTS table_name (
  id BIGINT UNSIGNED NOT NULL AUTO_INCREMENT,
  gmt_create DATETIME,
  gmt_modified DATETIME,
  PRIMARY KEY (id)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=utf8;
字段类型选泽


