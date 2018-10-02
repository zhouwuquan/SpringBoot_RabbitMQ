# SpringBoot_RabbitMQ
使用SpringBoot搭建环境，学习使用RabbitMQ
简介：本课程主要带大家快速入门RabbitMQ消息中间件基础，会带着小伙伴快速搭建环境，并进行核心基础的学习，之后整合springboot2.x，
	  最后做一个在真正生产环境中的高可靠性投递消息的实战案例（代码详解）。
课程导航:
	RabbitMQ简介及AMQP协议
	RabbitMQ安装与使用
	RabbitMQ核心概念
	RabbitMQ与Springboot2.X整个-急速入门
	保障100%的消息可靠性投递方案落地实现

1、首先安装erLang包，因为RabbitMq是基于erLang语言开发的,http://www.erlang.org/downloads
2、安装RabbitMq,下载地址：http://www.rabbitmq.com/download.html
3、Springboot整合RabbitMQ集成非常简单，不需要做任何的额外设置，只需要两步即可。
	step1、引入依赖包
		<!-- amqp是Rabbit -->
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-amqp</artifactId>
      	</dependency> 
	step2、对application.properties进行配置

见CSDN博客