# 学习大纲

> - JavaScript基础
> - Web APIs
> - JavaScript进阶



# 基础第一天

## 学习目标

> - 1.理解变量是存储数据的“容器”
> - 2.理解什么是数据并知道数据的分类
> - 3.知道JavaScript数据类型转换的特征

## JavaScript介绍

### Javascript属性介绍

#### 1..JavaScript(是什么？)

> 是一种运行在客户端（浏览器）的编程语言，实现人机交互效果。

#### 2.作用(做什么？)

> - 网页特效（监听用户的一些行为让网页作出对应的反馈）
> - 表单验证（针对表单数据的合法性进行判断）
> - 数据交互(获取后台的数据，渲染到前端)
> - 服务端编程(node.js)![image](assets/image-20230510224725-v8g1ot2.png)

#### 3.JavaScript的组成(有什么？)

![image](assets/image-20230510224936-4qxmrn3.png)



##### ECMAScript:

> - 规定了jS基础语法核心知识。
>   - 比如：变量、分支语句、循环语句、对象等等

##### Web APIs:

> - DOM
>   - 操作文档，比如对页面元素进行移动、大小、添加删除等操作
> - BOM
>   - 操作浏览器，比如页面弹窗，检测窗口宽度、存储数据到浏览器等等

JavaScript权威网站：https:/developer.mozilla.org/zh-CN/docs/Web/JavaScript

### JavaScript书写位置

#### CSS位置

> - 行内样式表
> - 内部样式表
> - 外部样式表

#### JavaScript

> - 行内JavaScript
> - 内部JavaScript
> - 外部JavaScript

##### 1.内部JavaScript

> - 直接写在html文件里，用script标签包住
> - 规范：script标签写在</body>上面
> - 拓展：alert('你好，js')页面弹出警告对话框
>
> ```javascript
> <!DOCTYPE html>
> <html>
> 	<head>
> 		<meta charset="utf-8">
> 		<title></title>
> 	</head>
> 	<body>
> 		<script>
> 		
> 			alert("Hello World!")
> 			// 页面弹出警示框
> 		</script>
> 	</body>
> </html>
> ```

> - 注意事项
>   - 我们将<script>放在HTML文件的底部附近的原因是浏览器会按照代码在文件中的顺序加载HTML
>   - 如果先加载的JavaScript期望修改其下方的HTML,那么它可能由于HTML尚未被加载而失效。
>   - 因此，将JavaScript代码放在HTML页面的底部附近通常是最好的策略。

##### 2.外部JavaScript

> - 代码写在以.js结尾的文件里
> - 语法：通过script标签，引入到html页面中
>
> ```javascript
> <!DOCTYPE html>
> <html>
> 	<head>
> 		<meta charset="utf-8">
> 		<title></title>
> 	</head>
> 	<body>
> 		<script src="01.js">		
> 		</script>
> 	</body>
> </html>
> ```

> - 注意事项
>   - 1.script标签中间无需写代码，否则会被忽略！
>   - 2.外部JvaScripts会使代码更加有序，更易于复用，且没有了脚本的混合，HTML也会更加易读，因此这是个好的习惯。

##### 3.内联JavaScript

> - 代码写在标签内部
> - 语法：
> - 注意：此处作为了解即可，但是后面vue框架会用这种模式
>
> ```javascript
> <body>
> 	<button onclick="alert('逗你玩~~')">点击我月薪过万</button>
> </body>
> ```

##### 总结

> - 1.JavaScript三种书写位置？
>
> - 内部
> - 外部
> - 行内

> - 2.注意事项：
> - 书写的位置尽量写到文档末尾</body>前面
> - 外部jS标签中间不要写代码，否则会被忽略

### JavaScript的注释

### JavaScript的结束符

### 输入和输出语法

### 字面量

## 变量

## 常量

## 数据类型

## 类型转换

## 实战案例