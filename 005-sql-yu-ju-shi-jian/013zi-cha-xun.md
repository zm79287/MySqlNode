#### 子查询

- 在一个select 语句中, 嵌入了另一个 select语句, 那么被嵌的select语句被称之为子查询语句.

#### 主查询
- 主查询的对象, 第一条select语句

#### 主查询和子查询的关系
- 子查询是嵌入到主查询中
- 子查询是辅助主查询的, 要么充当条件, 要么充当数据源
- 子查询是可以独立存在的语句, 是一条完整的select语句

#### 子查询分类
- 标量子查询: 子查询返回的结果是一个数据(一行一列)
- 列子查询: 返回的结果是一列(一列多行)
- 行子查询: 返回的结果是一行(一行多列)
- 表级子查询: 返回的结果是多行多列

#### 标量子查询