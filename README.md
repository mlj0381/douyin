﻿## 目录结构

	.
	├── img            	   视频封面存储目录
	├── v            	   视频存储目录
	├── sql           	   数据库结构文件存放目录
	├── class.txt          存放需要采集的挑战id
	├── down.txt           存放需要下载的视频分类
	└── README.md          说明

## 格式说明

	* 存放需要采集的挑战id，格式为：“挑战id;挑战名称;分类名称”，一行一个，注意文件保存格式utf-8

	* 存放需要下载的视频分类，格式为“分类名;需要下载的数量;是否下载封面”，
	    注：每个参数之间必须用半角分号分隔开，即使不填值
	           参数“需要下载的数量”不填或者填0表示全部下载，
	           如果需要下载封面的话“是否下载封面”的值为1，否则不填

