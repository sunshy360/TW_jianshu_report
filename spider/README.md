# Useage

下载zip或者clone此项目  

``` cd jianshu-spider ```  

``` bundle ```  

``` ruby jianshu-spider.rb "用户名" "文章参数" ```  

比如``` ruby jianshu-spider.rb "吴立宁" "*" ```  

![示例图片](./示例图片.png)

比如日期参数``` ruby jianshu-spider.rb "吴立宁" "2016-03-10 2016-03-20" ```  
![示例图片](./示例图片2.png)

# spider模块

``` require "spider" ```  
``` uuid = Spider.getUUID("用户名") ```
``` articles = Spider.getLatestArticles("用户名") ```
