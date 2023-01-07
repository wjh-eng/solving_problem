# EXE打包所需库

在新目录下放入需要打包的.py文件

```python
pip install pipenv
# 创建虚拟环境 默认在个人目录.virtualenvs
pipenv install --python 3.6
pipenv shell   # 进入虚拟环境

# 虚拟环境安装所需要的库
pipenv install pyinstaller
pipenv install pyqt5
pipenv install pymysql
pipenv install geopy


# -F是所有库文件打包
# -w是运行exe文件时禁止弹出黑色控制台窗口
pyinstaller -F -w Select_Data.py

# dict文件夹中有.EXE文件
```

