功能： 将excel 文件中设计的数据库转化为laravel 中 migrations要使用的方法

字段名分别为column（字段名）	type（数据类型）	length（长度）	indexes（索引/主键）	default（默认值）	nullable（是否为空）     remark（备注）
	
注意：如果是表中的字段，必须填写nullable，因为是由这个字段判断是否是一个表的；否则将nullable 放空

转化完成可在 控制台（console） 查看