## 记录下生成文档的步骤

### 1.安装需要的库
******
pip install sphinx  
pip install recommonmark  #md文件需要

### 2.把python文件转化成sphinx源文件
******
sphinx-apidoc -o ../vnpy ./source/vnpy

### 3.修改conf.py文件

### 4.修改index.rst文件

### 5.生成html
******
./make html

### 6.预览
******
1）进入目录 build\html,打开命令行；  

2）执行命令：python -m http.server  

3）在浏览器输入“127.0.0.1:8000”





https://sphinx-doc.cn/en/master/man/sphinx-apidoc.html
