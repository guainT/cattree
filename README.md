# cattree
无限级分类小模块
免费看了个视频，留的课后作业，
视频地址：https://www.bilibili.com/video/BV1bJ411i7ZP
书就不用送我了。感谢学习猿地的老师。
mysql表结构：

CREATE TABLE `category` (
  `id` int(11) unsigned NOT NULL AUTO_INCREMENT,
  `catename` varchar(30) COLLATE utf8_unicode_ci DEFAULT NULL,
  `pid` int(11) DEFAULT '0',
  `ord` int(11) DEFAULT '0' COMMENT '排序',
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=30 DEFAULT CHARSET=utf8 COLLATE=utf8_unicode_ci


