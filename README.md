# Mysql2docx
自动生成数据库设计文档

安装
pip3 install python-docx
pip3 install Mysql2docx


使用
```python
>>> from Mysql2docx import Mysql2docx
>>> m=Mysql2docx()
>>> m.do('127.0.0.1','root','password','dbName',3306)
```

截图
![](https://gitee.com/icecooly/Mysql2docx/attach_files/download?i=92254&u=http%3A%2F%2Ffiles.git.oschina.net%2Fgroup1%2FM00%2F01%2FC2%2FPaAvDFmfB1aAJHJAAAKrDJmxm3s571.png%3Ftoken%3Dbe03962b66f41ed6121c126d92238e70%26ts%3D1503594613%26attname%3Ddoc1.png)