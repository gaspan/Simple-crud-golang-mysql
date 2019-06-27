#How to Run this Web

-create db wich name is goblog
- create table :
DROP TABLE IF EXISTS `employee`;
CREATE TABLE `employee` (
  `id` int(6) unsigned NOT NULL AUTO_INCREMENT,
  `name` varchar(30) NOT NULL,
  `city` varchar(30) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;

- donwload mysql driver by typing: "go get -u github.com/go-sql-driver/mysql"
- run web by following command : "go run main.go"
- open browser "http://localhost:8080/"