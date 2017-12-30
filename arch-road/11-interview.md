# 面试题

# java基础方面
1. 集合 
	- ArrayList/LinkedList
	- Map/Set TreeSet Set与Map的关系
2. 并发包
	- AtomicInteger  CAS
	- ConcurrentHashMap/ConcurrentMap(Collections) java8做了哪些改进
	- 队列 BlockingListQueue
	- 线程池 如何定线程池大小（公式）
	- Timer/ScheduledThreadPoolExecutor
3. java8新特性
	- interface 默认方法
	- lambda表达式
4. 反射
5. Lock
	- ReentrantLock
	- ReadWriteLock
	- synchronized
	- 哪些机制可以避免锁  CAS/copy-on-write
6. volatile
	- java内存模型  （可见性/顺序）




# 框架方面
1. spring IOC/AOP 事务 spring-boot
	- test怎么做
	- MockMVC
	- @Bean注解的方法
	- spring-boot最大的亮点是什么
	- spring-mvc原理 （web.xml/servlet 3.0注解）
	- 拦截器 Interceptor 与filter区别
	- @Transaction原理  什么时候会失效
2. mybatis 
	- 拦截器 
	- typeHandler 
	- 动态sql
3. 安全框架
	- shiro
	- Spring-security
	- Oauth2
4. 设计模式
	- spring里面用到的设计模式
	- 约定优于配置 conversion over configuration  (maven/spring-boot)


# 计算机基础
1. TCP UDP
2. Https SecureRandom 随机数生成原理（linux）
	- dev/./urandom dev/./random
3. DNS
4. Http 2.0
	- push
	- Comet
	- long poll
5. 文件打开数ulimit
	- http time_wait
6. keep-alive



# 架构方面
1. 接入层 openresty
	- 限流/鉴权
2. 缓存
	- 浏览器
	- http头 last-modify control
	- nginx 缓存
	- web层缓存
	- 服务层缓存
3. Redis 遇到什么问题
	- 数据结构
	- Zset问题 （skipList）
4. mysql
	- 分库分表
	- id生成器（snowflake）
	- 覆盖索引
	- 索引与PK区别
	- 事务隔离级别
		- 读未提交
		- 读已提交
		- 可重复读
		- 序列化读
	- binlog
	- 分布式
	- mvcc
	- 死锁
5. MQ
	- 事务（分布式事务）
	- 幂等
	- RocketMQ/Kafka
6. Netty/NIO
	- bio
	- aio 异步
	- nio
	- pool  （byteBuf）
7. 微服务 dubbo/spring-cloud
8. zookeeper
	- zab
	- Raft/Paxos
9. nginx/lvs 4层/7层代理
10. 限流/熔断
11. 分布式存储  levelDB(LSM树）
12. 一致性hash
13. jetty/tomcat  servlet3.1 异步
14. ES （搜索引擎/倒排索引）
15. 分布式协议
	- RNW模型 Amazon s3 Dynamo 
	- Raft
	- Paxos 腾讯的PhxMysql  阿里的OsceanBase
16. maven
	- 插件
17. git
	- rebase
	- 最佳实践(多人开发)
18. 灰度发布
	- AB
	- uid取hash
19. 压测
	- AB
	- jmeter
20. 分布式追踪系统
	- dapper  google
	- twitter zipkin
	- apache htrace
	- spring-cloud sleuth
	- dubbox 当当
	- dubbok 网易考拉
	- 淘宝eagleEye鹰眼
	- 美团cat
	- 京东hydra



# JVM方面
1. GC种类（原理）
2. WeakReference/SoftReference/StrongReference
3. 逃逸分析
4. 锁优化（StringBuilder StringBuffer) 
	- 偏向锁
	- 轻量级锁
	- 重量级锁
5. Integer(-128~127)缓存 ，可以修改
6. jstack/jmap
7. classloader (双亲委托/解决什么问题)
8. Class.forName() 将class load到 jvm后，再执行static块 区别于ClassLoader.loadClass



# 监控
1. 机器监控io/net/cpu
2. 应用监控 端口/ip/心跳检查
3. 业务监控 成功/失败/异常


# 讨论
1. mysql/oracle 如何实现强一致



# 其他
1. 关注的博客/公众号
2. 最近看的一本书
