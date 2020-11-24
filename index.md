Hello and welcome to this blog. Edit the `index.md` file to change this content. All pages on the blog, including this one, use [Markdown](https://guides.github.com/features/mastering-markdown/). You can include images:

![Image of fast.ai logo](images/logo.png)

## This is a title
### MyBatis入门教程
第一步，读取配置文件；	<br/>
第二步，创建SqlSessionFactory工厂；	<br/>
第三步，创建SqlSession；	<br/>
第四步，创建Dao接口的代理对象；	<br/>
第五步，执行dao中的方法；	<br/>
第六步，释放资源	<br/>

	注意：在映射配置中告知mybatis要封装到哪个
              实体类中；
	      配置的方式：指定实体类的全限定类名
	
	mybatis基于注解的入门案例：
		把IUserDao.xml移除，在dao接口的方法上使用@select注解，指定sql语句；
		同时需要在SqlMapConfig.xml中的mapper配置中，使用class属性指定全限定类名。




And you can include links, like this [link to fast.ai](https://www.fast.ai). Posts will appear after this file. 
