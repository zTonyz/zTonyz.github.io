#10.19 实验小结
##步骤：  
###一、准备开发环境  
1. 安装NodeJS ;    
1. 打开cmd命令行窗口：      

 `开始->运行->cmd，或键盘快捷键Ctrl+R->cmd，或开始->附件->命令提示符;`
###二、配置开发环境  
###2.1 安装Gulp任务管理器     
在cmd中，运行命令:
      
  **npm install -g gulp** 
                       
  等待成功提示，如果有错误提示，请报告    
###三、项目开发  
###3.1 下载网页应用项目脚手架（基本模板） 
下载或者复制得到 web-starter-kit ,并解压。  
  
假定解压后所在目录为E:\web-starter-kit-0.6.4所在目录： 
###3.2 准备项目开发依赖插件 
3. 在cmd中，切换到web-starter-kit-0.6.4所在目录： 
 
切换“盘符”：`>d:回车，或>e:回车；`  

切换“路径”：`>cd aa\bb\cc,注意使用tab键`  

4. 运行命令：安装网站运行环境：   
 
**`npm.install`**  

等待成功提示，如果有错误提示，请报告 
###3.3 进行项目开发 
###3.3.1 启动网站服务器  

**gulp serve**
  
系统会自动打开Firefox或Chrome浏览器，并打开项目网站首页：  
http://本机ip:3000 或 http://lochlhost:3000  
###3.3.2 编辑网页  
使用记事本或文本编辑器 或者专业的代码编辑器编辑网页文件(index.html或者CSS文件或者app.js脚本)，改为自己想要的效果  
###3.3.3 切换到浏览器查看修改后的效果  
原理上，网页的内容应该自动会刷新  
###3.3.4 在其它设备（Phone,tablet...）上查看网页效果  
确认看看跨设备的网页是否有同步显示  
  
  
###3.3.5 继续重复3.3.2-3.3.4的步骤，不断修改网页，最终达到自己想要的效果  
###3.3.6 结束开发  
关闭代码编辑器  
在gulp serve的cmd窗口，按CTRL+C结束服务器的运行  
关闭浏览器的网页  
  
  至此，一个初始的简单网站及其运行环境就安装好了，接下去的工作就是更多页面的制作和内容的添加、更新，以及后续的维护和管理  
  
##说明：  
1. 吴老师讲得比较快、信息量大，有些同学没弄明白在做什么，其实就是利用现成的模版（*web-starter-kit-0.6.4*）建立了一个空网站、只有一个主页，之后才是网页的设计和制作，好比先建好一个电视台，然后再设置不同的频道、加入各种各样的节目。  
1. web-starter-kit-0.6.4、app目录下，index.html就是主页文件，`右键点击->打开方式->选择“记事本”`，可以看到html代码，对照浏览器上显示的主页，大家学习一下html的语法，http://www.w3school.com.cn 有详细教程。  
看不懂也没关系，刚开始先有个大致了解就可以，后面就慢慢熟悉了。  
1. 大家留意一下自己经常上的网站，看看那些网页的布局、功能都有哪有特点，想一想接下来你自己的网页要怎么设计。  
2. 上课也可以自己带电脑，操作起来会更熟练，回去之后接着做也会比较方便。
