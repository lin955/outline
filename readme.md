# Javascript基础语法

## js历史
* liveScript -> javascript
* JScript
* ECMAScript（标准化javascript，简称ES）
    * ES6 -> 2015
    * ES7 -> 2016
    * ES8 -> 2017
    * ES9 -> 2018
    * ES10 -> 2019
    * ES11 -> 2020
* Mozilla（firefox）

## js语言的组成
> javascript = ECMAScript + BOM + DOM

## H5与前端js的关系
> h5全称HTML5,不是单纯的html的第5个版本，而是一项最新的web标准，是html、css、javascript等技术的集合
* 前端与后端


## 基础语法
* js编写位置
    * script
        > script标签可以写在任何位置，但建议放在body内且放在所有便签后端
        * type
        * src
    * 单独文件  
* 变量声明
    > 变量：数据的容器
    * 变量命名规则：
        * 变量名必须是数字,字母,下划线`_`和美元符`$`组成;
        * 第一个字符不能为数字
        * 不能使用关键字或保留字
* 关键字
    * var
* 注释
    > 浏览器会忽略注释后的内容
    * `//`  单行注释
    * `/**/` 多行注释
* 输出测试
    * alert()   弹窗输出
    * console.log() 控制台输出
    * 元素输出
        * 表单：元素.value
        * 双标签元素：元素.innerHTML = 值
    * document.write()  输出到body

## 数据类型
* String    字符串（**单引号**或**双引号**包含的数据）
* Number    数字
    > 0-9
    * NaN: Not a Number
* Boolean   布尔值
    * true  对/是/1
    * false 错/否/0


### 数据类型转换
* 显性转换
    * String -> Number : Number(字符串)
    * Number -> String : String(数字)
    * Number -> Boolean : Boolean(数字)
* 隐式转换
    > 如果运算不能进行下去，内部就会尝试进行数据类型的自动转换(支持隐式转换的运算：逻辑运算、关系运算、算术运算）

## 运算
### 算术运算
> 针对数字类型

* 加法：+
    * 数字：加法运算
    * 字符串：拼接
* 减法：-
* 乘法：*
* 除法：/
* 求余（求模）：%


### 赋值运算
* =
* +=
* -=
* *=
* /=
* %=


## 常用方法
* parseInt()    取整
* toFixed()     取小数点位数



## 超前知识点
* 获取元素：`document.getElementById()`
    * 获取表单的值：`元素.value`  得到的数据为String
    * 写入表单的值：`元素.value=值`
* 事件绑定：`元素.onclick=function(){}`