## jinja2 模板语法
+ 继承  `{% extends "父模板路径"%}`
+ 数据块 `{% block 块名 %} ... {% endblock %}`
+ 路由生成 `{{ url_for("模块名.视图名")}}`
+ 静态文件加载 `{{ url_for('static',filename='静态文件路径')}}`
+ 循环语句 `{% for 条件%} ... {% endfor %}`
+ 条件语句 `{% if 条件%} ... {% endif %}`

## requirement
```
pip install flask-sqlalchemy==2.1  
pip install SQLAlchemy
pip install flask-wtf
pip install WTForms
pip install pillow
```
## refer
- [pythondoc](http://www.pythondoc.com/)
- [bootstrap中文](https://v4.bootcss.com/)
- [bootstrap](https://getbootstrap.com/docs/4.1/getting-started/introduction/)