从这里开始
====================


欢迎来到sumeru的世界，在这里，您将获得超乎想象、无比便捷的开发体验。





sumeru基于node.js开发，可使用npm获取。

	npm install -g sumeru
	
现在，我们创建一个sumeru项目。

	sumeru init ./myproject
	
myproject是项目所在目录，你可提前创建，也可由sumeru自动创建。
	
在每一个生成项目中，都会有一个可运行的应用,首先使用下面的命令启动sumeru。

	cd myproject
	
	sumeru start
	
然后在浏览器中输入 localhost:8080/debug.html#/itworks 第一次运行sumeru。

![](images/itworks.png)

同时我们也提供手动下载方式，[点击这里下载](http://baidu.com)







	通过router添加一个URl与Controller的映射关系，关于router我们会在后续文档中做专门的说明，保持helloworld.js文件打开，并输入以下代码。
	
		App.helloworld = sumeru.controller.create(function(env,session){



	









** 至此 **，"hello world"应用代码已经完成。

在浏览器中输入"localhost:8080/debug.html#/helloworld"运行该应用。

![](images/helloworld.png)

你可能已经发现，一个sumeru的项目有以下目录组成

![](images/sumeru_folder.png)

对于sumeru目录在后续会做专门的介绍。