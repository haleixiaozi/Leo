Leo
===

接口自动化测试框架 1.0.4

1.0.5-SNAPSHOT 更新内容
-------------------------------
1. 解决生成javadoc时WARNING;
2. 当预期结果为int类型时，对实际结果为0进行判断(0为int结果匹配中的特殊值);



1.0.4 更新内容：
-------------------------------
1. 增加设置预期结果中"date"关键词dateFormat样式，可自定义关键词date样式;
2. 预期结果中增加对int关键词的支持，匹配结果中int类型动态值,支持单个和多个实际结果（key=int或key=int^int）;
3. 增加Host关键字及全局配置;
4. 增加Header全局配置;
5. 修改注解;


1.0.3 更新内容：
-------------------------------
1. pom.xml中增加邮件包依赖;  
2. 增加https请求处理（支持证书认证与非证书认证两种方式）
3. 修改解析xml时一个key对应多个值时，实际结果值与预期结果值无法进行比较（key=value1^valu2）
4. CompareResult.trimActres 修改为public类型提供业务处理使用;
5. 修改代理默认值bug;