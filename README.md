# jest-client-demo
JestClient通过写json来实现对ElasticSearch的操作,
使用jestClient比较明显的一个优势,不用因为es的版本升级导致API发生改变而更改代码。

```
	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>2.1.0.RELEASE</version>
		<relativePath/> <!-- lookup parent from repository -->
	</parent>
	
	<dependency>
		<groupId>org.elasticsearch</groupId>
		<artifactId>elasticsearch</artifactId>
		<version>5.6.9</version>
	</dependency>
	<dependency>
		<groupId>io.searchbox</groupId>
		<artifactId>jest</artifactId>
		<version>5.3.4</version>
	</dependency>
```

ESService.java跳转:
https://github.com/TianShengBingFeiNiuRen/jest-client-demo/blob/master/src/main/java/com/andon/jestclientdemo/service/ESService.java

CSDN:
https://blog.csdn.net/weixin_39792935/article/details/84328897
