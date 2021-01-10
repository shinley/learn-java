# spring session
spring-session技术解决同域名下的服务器集群session共享问题， 不能解决跨域session共享问题民

使用： 配置一个Spring提供的Filter,实现数据的拦截保存，并转换为spring-session需要的会话对象

必须提供一个数据库的表格信息（由spring-session提供）

