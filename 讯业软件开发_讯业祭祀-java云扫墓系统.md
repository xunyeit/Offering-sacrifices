<font style="color:#000000;">讯业软件开发/讯业祭祀-java云扫墓系统</font>

## <font style="color:#000000;">一、产品概述</font>
**<font style="color:#000000;">云祭祀系统主要是有公共纪念馆展示烈士英雄可敬献礼物写留言，创建私人纪念馆在墓碑中选一个序列号，创建纪念馆填写逝者资料信息，生成私人纪念馆，可敬献供奉礼物。分为用户端小程序、后台管理系统</font>**

**<font style="color:#000000;"></font>**

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773214595693-e527688b-f98e-488d-98f1-b8ef6ed1d126.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773214611076-2262a708-d217-41b3-a96b-a7d6f7857420.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773214625923-46dc94e0-a087-4a03-9b80-9c3784eac1f8.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773214635911-030ffd6f-9593-41c6-a370-1d716e57a097.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773214644904-490a8887-d8c1-42ec-8f92-58cd49622850.png)

<font style="color:#000000;"></font>

## <font style="color:#000000;">首页</font>
**<font style="color:#000000;">公共纪念馆：纪念馆列表，点击查看纪念馆详情，留言，敬献礼物  
</font>****<font style="color:#000000;">私人纪念馆：选择一个墓碑序列号，创建纪念馆（可选单人馆/双人馆），上传逝者头像，填写逝者姓名、出生日期、逝世日期、祖籍；选择背景模板、背景音乐、是否公开、生平简介、回忆相册；双人馆依次填写上信息，点击快速创建，创建好的纪念馆在私人纪念馆列表展示。进入纪念馆可以  
</font>****<font style="color:#000000;">纪念馆留言：留言列表展示。</font>**

## <font style="color:#000000;">我的</font>
**<font style="color:#000000;">心灵家书：展示写过的家书。  
</font>****<font style="color:#000000;">我的家书：写一封家书，填写标题 内容，发布家书。  
</font>****<font style="color:#000000;">我的祈福：敬献过的礼物。  
</font>****<font style="color:#000000;">我的留言：在纪念馆写过的留言。</font>**

## <font style="color:#000000;">后台</font>
**<font style="color:#000000;">创建公共纪念馆，填写纪念馆信息保存，创建私人纪念馆墓碑，分类、二级分类、墓碑几排几号，创建完之后展示在私人纪念馆墓碑列表。后台可以上传背景音效，背景图，敬献礼物。</font>**

**<font style="color:#000000;"></font>**

## <font style="color:#000000;">架构特点</font>
### <font style="color:#000000;">架构特性</font>
+ **<font style="color:#000000;">前后端分离架构，独立开发，符合主流开发模式</font>**
+ **<font style="color:#000000;">前端以Vue3+Vite为主技术，AntdV为UI界面框架</font>**
+ **<font style="color:#000000;">后端SpringBoot3为基础，MybatisPlus为数据操作框架，Redis为缓存框架</font>**
+ **<font style="color:#000000;">Maven多模块管理，插件化开发，方便安装、卸载、升级，降低耦合</font>**
+ **<font style="color:#000000;">业务模块与API抽离，模块之间便捷引用</font>**
+ **<font style="color:#000000;">数据库设计精巧，字段规范、易于扩展</font>**
+ **<font style="color:#000000;">支持国产密码算法加解密，等保测评国产项目无压力</font>**
+ **<font style="color:#000000;">支持MYSQL、ORACLE、SQLSERVER、PGSQL等主流标准结构式数据库</font>**
+ **<font style="color:#000000;">支持达梦、人大金仓、南大通用、九有、瀚高、虚谷数据库等国产数据库</font>**
+ **<font style="color:#000000;">支持中创、宝蓝德、东方通等中间件</font>**
+ **<font style="color:#000000;">支持Windows、Linux操作系统、国产操作系统部署</font>**

### <font style="color:#000000;">功能特性</font>
+ **<font style="color:#000000;">完善的系统基础功能，满足使用需求，避免重复造轮子</font>**
+ **<font style="color:#000000;">支持本地文件、阿里云文件、腾讯云文件、MINIO文件上传</font>**
+ **<font style="color:#000000;">支持本地邮件、阿里云邮件、腾讯云邮件发送</font>**
+ **<font style="color:#000000;">支持阿里云短信、腾讯云短信发送</font>**
+ **<font style="color:#000000;">B、C端双账号认证体系，会话治理各自独立</font>**
+ **<font style="color:#000000;">完善的登录日志、操作日志、异常日志等审计功能</font>**
+ **<font style="color:#000000;">完善的会话监控、数据源监控、系统监控等必备监控功能</font>**
+ **<font style="color:#000000;">支持组织机构、权限管理、定时任务、系统配置等基础功能</font>**

### <font style="color:#000000;">安全特性</font>
+ **<font style="color:#000000;">采用SaToken轻量级 Java 权限认证框架，功能强大、学习成本低</font>**
+ **<font style="color:#000000;">支持登录认证、权限认证、单点登录、三方登录、OAuth2.0等认证模式</font>**
+ **<font style="color:#000000;">增强的RBAC权限设计，资源于接口独立授权，更加灵活</font>**
+ **<font style="color:#000000;">支持按钮级别细粒度独立授权，界面按钮动态展示</font>**
+ **<font style="color:#000000;">支持API接口注解式、路由拦截式鉴权，防止越界访问</font>**
+ **<font style="color:#000000;">独创的数据范围机制，每个接口都可以配置不同数据范围</font>**
+ **<font style="color:#000000;">支持限流防抖，防重复提交，有效阻止脏数据产生</font>**
+ **<font style="color:#000000;">密码、手机、身份证号等使用国密算法加密传输、加密存储，数据更安全</font>**
+ **<font style="color:#000000;">操作日志使用SM2进行完整性保护，满足安全审计要求</font>**

### <font style="color:#000000;">界面特性</font>
+ **<font style="color:#000000;">Vue3 + Vite为基础，AntdV为界面UI框架，视觉风格清新简洁</font>**
+ **<font style="color:#000000;">精细化设计，注重界面的每一处细节，操作轻松友好</font>**
+ **<font style="color:#000000;">暗黑风格、经典菜单、双排菜单、多页签、目录坞、主题切换等功能应有尽有</font>**
+ **<font style="color:#000000;">统一的网络框架、API接口拦截框架，拿来即可上手</font>**

**<font style="color:#000000;"></font>**

**<font style="color:#000000;">联系交流</font>**

公司官网：[https://www.xunyeit.com](https://www.xunyeit.com)

案例库：[https://cms.xunyeit.com/](https://cms.xunyeit.com/)

**<font style="color:#000000;">交流微信：</font>**<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773214693979-80b8d005-926e-42a4-b2bf-8a041f3c1ed0.png)

