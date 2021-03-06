# 第10讲 ：正则表达式和ES6
by ZHAO Jing

## 字符串
### API

- charAt()	返回指定索引位置的字符
- charCodeAt()	返回指定索引位置字符的 Unicode 值
- concat()	连接两个或多个字符串，返回连接后的字符串
- fromCharCode()	将 Unicode 转换为字符串
- indexOf()	返回字符串中检索指定字符第一次出现的位置
- lastIndexOf()	返回字符串中检索指定字符最后一次出现的位置
- localeCompare()	用本地特定的顺序来比较两个字符串
- match()	找到一个或多个正则表达式的匹配
- replace()	替换与正则表达式匹配的子串
- search()	检索与正则表达式相匹配的值
- slice()	提取字符串的片断，并在新的字符串中返回被提取的部分
- split()	把字符串分割为子字符串数组
- substr()	从起始索引号提取字符串中指定数目的字符
- substring()	提取字符串中两个指定的索引号之间的字符
- toLocaleLowerCase()	根据主机的语言环境把字符串转换为小写，只有几种语言（如土耳其语）具有地方特有的大小写映射
- toLocaleUpperCase()	根据主机的语言环境把字符串转换为大写，只有几种语言（如土耳其语）具有地方特有的大小写映射
- toLowerCase()	把字符串转换为小写
- toString()	返回字符串对象值
- toUpperCase()	把字符串转换为大写
- trim()	移除字符串首尾空白
- valueOf()	返回某个字符串对象的原始值
### 正则表达式
正则表达式修饰符
修饰符 可以在全局搜索中不区分大小写:

修饰符	描述
i	执行对大小写不敏感的匹配。
g	执行全局匹配（查找所有匹配而非在找到第一个匹配后停止）。
m	执行多行匹配。

正则表达式模式
方括号用于查找某个范围内的字符：

表达式	描述
[abc]	查找方括号之间的任何字符。
[0-9]	查找任何从 0 至 9 的数字。
(x|y)	查找任何以 | 分隔的选项。
元字符是拥有特殊含义的字符：

元字符	描述
\d	查找数字。
\s	查找空白字符。
\b	匹配单词边界。
\uxxxx	查找以十六进制数 xxxx 规定的 Unicode 字符。
量词:

量词	描述
n+	匹配任何包含至少一个 n 的字符串。
n*	匹配任何包含零个或多个 n 的字符串。
n?	匹配任何包含零个或一个 n 的字符串。

## JS函数式编程和算法：
### 函数式编程:
- map
- reduce
- filter
- reverse
- sort
- split
- join
- forEach

## FCC算法 in JS
- 初级算法
- 中级算法
- 高级算法
