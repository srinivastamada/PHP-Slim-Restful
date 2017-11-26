# PHP-Slim-Restful
```
CREATE TABLE users(
user_id int AUTO_INCREMENT PRIMARY KEY,
username varchar(50),
password varchar(300), 
name varchar(200), 
email varchar(300)); 
 
CREATE TABLE feed(
feed_id int PRIMARY KEY AUTO_INCREMENT, 
feed text,
user_id_fk int,
created int
);

CREATE TABLE `emailUsers` (
  `user_id` int(11) PRIMARY KEY AUTO_INCREMENT,
  `email` varchar(300) DEFAULT NULL,
  `name` varchar(100) DEFAULT NULL
) 

CREATE TABLE `imagesData` (
  `img_id` int(11) PRIMARY KEY AUTO_INCREMENT,
  `b64` text DEFAULT NULL,
  `user_id_fk` int(11) DEFAULT NULL
) 
```
