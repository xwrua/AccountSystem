1.确保以下4个文件放在同一目录下:
[
	account.jar,
	account.bat,
	log4j.properties,
	account_lib文件夹
]
2.运行account.bat,之后便会看到用户界面

配置文件:
1.打开程序,在目录下会自动生成一个config.txt,存放配置信息
2.若要手动修改配置信息,请先将程序关闭
3.添加员工时,在"employees"行填写员工姓名并用逗号隔开,保存文件,重启程序来重新加载配置

插入数据:
点击"添加"按钮,在弹出界面添加数据
1.可以通过把文件拖动到下方来录入到一张新的表(读入文件功能只会读第一张表,表名为文件名)
(当勾选中"手动配置"时,将会按照你的设置导入)
(若不勾选"手动配置"时,表必须有表头,而且表头以下的列必须是数据.)
(
当勾选中"指定日期"时,在"日期列名"框内填入欲视为日期导入的列名(不是列编号)
同时若勾选中"格式化文本"时,在"格式化文本"框内填入格式化文本,参见附录1
)
2.当数据添加成功时,会弹出"添加成功"提示框,否则弹出错误提示
3.需要在主界面点击"刷新",才会出现新增的表

检索数据:
1.从下拉框选中欲检索表名
(当勾选中"系统表"时,将会显示系统表,否则自动隐藏)
2.点击"检索"按钮,右侧列表便会显示表内所有数据
3.双击表时,会弹出对话框,选择要显示/隐藏哪些列

筛选表内数据:
1.查询欲筛选的表后,将左下角面板切换至"筛选"
2.在下拉框选择欲筛选的列名,填写相应信息
(其中文本和数值类型的值填写在文本框内,日期类型的值填写在日期框内)
(文本暂时只能选择等于)
3.点击"添加规则",可看到列表里出现了相应规则
4.点击"开始筛选",便可看到筛选结果,若要重新操作请点击上方"查询表"
5.在列表中选择规则,点击"删除"按钮便可删除规则

删除数据:
1.请确保列表内存在数据
2.选中欲删除的数据项
3.点击"删除"按钮

比较表:
1.点击"比较01",弹出界面
2.在首界面选择表1和表2,根据提示在文本框填上用于匹配的关键列名
3.点击按钮,成功后可回到主界面刷新查看表

对账:
1.点击"添加",弹出界面
2.将对账文件夹拖入"对账文件夹"文本框中
(文件夹内需要有"折扣表"&"对账表")
(可在"系统_EMP"表中查看有效员工,在"添加"页面左上方有"添加员工")
3.成功后,可以查询到以"导出_"开头的结果表
4.对账表内未录入的记录,对账记录下会填写"0",已录入则填写"1"

导出数据:
1.从下拉框选中欲导出表名
2.点击"导出XSLX"按钮,成功后可在运行目录下看到文件,文件名为表名

运行日志位于运行目录的log.txt内

可以通过调整窗口大小来看到更多数据

(
附录1:
yyyy：年  
MM：月  
dd：日  
hh：1~12小时制(1-12)  
HH：24小时制(0-23)  
mm：分  
ss：秒  
S：毫秒 
2018-06-04 18:13:56 对应 yyyy-MM-dd HH:mm:ss
)