# C++
用C++实现一个基于命令行界面的简单记账软件。
1)	软件基于命令行，以文本方式实现交互
2)	软件主要有两大功能：记账和查询，并提供“退出”选项
3)	数据需要做持久化保存，可以存储在文本文件中
注意！
a、要运行该程序需要先在目录中创建一个对应的文件夹用以保存数据。(在该程序中使用宏定义PATH)
b、经过我的测试，该程序有一个bug还没修复好。当记账时，输入以数字开头的数据，即便包含字符，例如输入“5t5”，也会记账成功。
