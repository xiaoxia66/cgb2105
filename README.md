   # Java面试 #

**点开了就收藏此站吧**

**一、Spring 整合Mybatis**

**1.配置数据数以及mybatis的jar包**

**2.整合mybatis配置文件，包括事务管理方式，和数据库管理方式等**

**3.配置mapper映射文件与数据库进行交互。**

**二、springboot整合springmvc**

**1、添加springmvc依赖，编辑pom.xml文件，添加web、thymeleaf依赖**

**2、配置springmvc核心对象，在application.properties文件中添加视图解析器配置（配置路径前缀和文件后缀）**

**三、springboot整合mybatis**

**1、添加mybatis启动依赖，并设置mybatis框架版本**

**2、mybatis简易配置：控制语句时长，sql日志的输出等信息**

**四、简单的说一 下springmvc的工作流程**

**1、用户发送请求给中央控制器，DispatcherServlet调用处理器映射器HandlerMapping返回HanderExecutionChain对象，此对象包含了拦截器和一些处理器。**

**2、中央处理器调用处理器适配器HandlerAdapter找到具体的处理器Controller(Handler),之后返回ModelAndView对象传给适配器并返回给中央处理器，视图再交给thymeleaf的视图解析器进行解析，对此逻辑视图名添加路径前缀和文件后缀。**

**3、中央处理器拿到解析后的view经过渲染最终返回给用户**





















     

