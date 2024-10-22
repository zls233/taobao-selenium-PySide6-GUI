# taobao-selenium-gui

## 简介

基于selenium和PySide6的淘宝网页信息爬虫gui程序，爬虫部分是课程作业，gui部分是做着玩的。

## 功能

* 手动登录并获取淘宝 Cookies，以便进行身份验证。
* 输入搜索关键词和页数进行商品爬取。
* 将爬取到的商品信息保存为 CSV 文件。
* 在用户界面中实时显示爬取进度和日志信息。

## 环境要求

* Python 3.x
* 安装以下库：
  * PySide6
  * pandas
  * selenium

## 安装依赖

使用 pip 安装所需库：

```bash
pip install -r requirements.txt
```

## 使用方法

1. 运行main.py，输入搜索关键词和需要爬取的页数。
2. 点击“获取 Cookie”按钮，手动登录淘宝账号，完成后点击确定。
3. 登录成功后，返回主界面，输入 Cookie 文件和 CSV 文件的路径（可使用默认路径）。
4. 点击“开始爬取”按钮，程序将开始爬取商品信息。
5. 爬取完成后，数据将保存到指定的 CSV 文件中，并在界面上显示商品信息。

## 注意事项

* 确保网络连接正常。
* 由于程序涉及自动化操作，请合理使用爬虫，遵循相关法律法规。
* 在使用时请确保你的行为不违反淘宝网站的相关规定。

## 许可证

本程序为开源软件，遵循 MIT 许可证。请自由使用和修改，但请保留原作者信息。

## 联系方式

若有任何问题或建议，请联系作者或在相关社区进行讨论。
