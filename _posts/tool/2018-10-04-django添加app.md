---
layout: post
category: 工具
---
1、添加app
python manage.py startapp myApp
2、修改主项目settings.py，在安装app列表中添加myApp
3、修改主项目urls.py的配置，include新的myApp的urls配置信息；
4、在myApp的urls配置中添加urls，使url与views中函数对应起来；
5、在views.py中编写处理函数。