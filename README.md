# cat_video_download
# 多线程下载猫咪视频
## 代码使用的python环境为：python3.6.5
## 执行代码前请安装相关库以及打开代码对以下全局变量进行设置
### 设置主页
homepage = 'https://www.82maopp.com'
### 要爬取的网页，只爬取其中一个模块，要想爬取其他模块的视频请自行更改模块网址
root_url = 'https://www.82maopp.com/vodtypehtml/28.html'
### 视频保存的目录（绝对路径），不存在则会自动创建
root_dir = 'E:/爬取/视频/猫咪/少女绝美/'
### 加载数据库文件（绝对路径），不存在则会自动创建
database = 'E:/爬取/log/log.db'
### 设置线程数，即可以同时下载视频的任务数量
max_tasks = 8
### 设置视频链接下载失败后的重试次数
retry_download = 5
