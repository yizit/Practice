以下题目为具体上机题，请按实际答题（建议针对每个问题创建一个项目来回答）：

题目1：
获取当前工作目录下所有的文件列表，并展示文件名称；

题目2：
手写一个字符串的扩展方法，根据指定的分隔符分割当前字符，并返回分割后的数组；

题目3：用sql脚本创建
数据库：practice
表：User
	字段：
	Id nvarchar(32)
	Name nvarchar(50)
	IdCard nvarchar(18)
	Phone nvarchar(11)
	Address nvarchar(100)

并以自己的身份信息模拟插入一条数据	

把以上的sql语句整理，并放入到当前解决方案中；

题目4：
手写一个支持线程安全的单例类；

题目5：
创建一个控制台应用程序的项目
手写一个基类BaseParseJob，有一个Task类型的属性ParseTask，以及一个命名为run无参无返回值的抽象方法；
手写一个类ParseJob继承自上一个基类，在构造函数中初始化属性ParseTask，并传入的action为run方法；
备注：在重写的run方法中实现每间隔10秒输出当前时间；
在外部新建类的实例后，然后启动parsetask，实现每间隔10秒输出当前时间



