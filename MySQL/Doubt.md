# MySQL疑难杂症

### 1、数据库乱码
```
mysql> SET charset gbk;
```
设置数据库编码
<br><br><br>


### 2、数据显示不对齐
默认设置：
```
mysql --default-character-set=latin1 -uroot -p
```
万国码设置（中文乱码用这个）：
```
mysql --default-character-set=gbk -uroot -p
```
设置中文字符集
<br><br><br>

