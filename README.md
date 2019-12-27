# flask_studentManagement
【个人Python-Flask项目】学生管理系统简化版
## 准备：
1. 安装virtualenv:
`pip install virtualenv`

2. 创建虚拟环境:
`virtualenv venv`

3. 进入虚拟环境:
`venv\Scripts\activate`

4. 安装依赖的包:
`pip install -r requirements.txt`

## 运行：
1. 更新数据库：`python app.py db upgrade`

2. 生成管理员用户：`python app.py init`

3. 运行：`python app.py runserver`

## 初始管理员账户：
```
学号：000000
密码：666666
```