# ssm-crud（增删改查核心业务）

#### 1、项目技术

使用 SSM（Spring、SpringMVC、MyBatis）框架 。Bootstrap 前端，JQuery脚本，Ajax请求，Maven依赖。

#### 2、项目简介

角色模型为：员工&部门，即多对一简单模型。

外键关系为：部门的编号是员工的外键，即fk_emp_dept。tbl_deptt的dept_id是bl_emp的d_id的外键。

功能流程为：Bootstrap的UI组件提交Ajax请求流入SpringMVC拦截器，流入对应的Controller，找到对应的Service，找到	对应的Dao，选择对应的Mapper，进入Ioc容器，提交到Mysql，再依次返回，发给前端Json，前端自行解析。

#### 3、项目导入

以maven 工程导入，修改jdk为1.8，tomcat为8.5。检查更新pom.xml依赖jar包，设置编码为UTF-8。修改数据库连接数据，mysql命令行运行sql文件，单元测试下批量添加数据。一切就绪后，启动项目。浏览器F12开启调试模式。


#### 4、深情致谢
[[尚学堂]](: http://www.atguigu.com/download.shtml)