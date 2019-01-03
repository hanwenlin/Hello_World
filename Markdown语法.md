Markdown是一种纯文本格式的标记语言。通过简单的标记语法，它可以使普通文本内容具有一定的格式。
#### 优点：
1. 因为是纯文本，所以只要支持Markdown的地方都能获得一样的编辑效果，可以让作者摆脱排版的困扰，专心写作。
2. 操作简单。比如:WYSIWYG编辑时标记个标题，先选中内容，再点击导航栏的标题按钮，选择几级标题。要三个步骤。而Markdown只需要在标题内容前加#即可
#### 缺点：
1、需要记一些语法（当然，是很简单。五分钟学会）。  
2、有些平台不支持Markdown编辑模式。

#### 1.1 关于换行
在a b c 的c后面,如果a b c 与d之间不空行,或者只在c后面空一格,在这个时候,按下回车的话,编辑的第二行d,会与a b c在同一行里 要想实现换行,需要至少需要在c的后面空两个空格
但是由于markdown编辑器的不同,可能在一行字后面,直接换行回车,也能实现换行,但是在Visual Studio Code上,想要换行必须得在一行字后面空两个格子才行.

# 一、标题
一个#是一级标题，二个#是二级标题，以此类推。支持六级标题。

注：标准语法一般在#后跟个空格再写文字，貌似简书不加空格也行。  
实例：  
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题


# 二、字体
+ #### 加粗
要加粗的文字左右分别用两个*号包起来
+ #### 斜体
要倾斜的文字左右分别用一个*号包起来
+ #### 斜体加粗
要倾斜和加粗的文字左右分别用三个*号包起来
+ #### 删除线
要加删除线的文字左右分别用两个~号包起来

实例：  
**这是加粗的文字**  
*这是倾斜的文字*`  
***这是斜体加粗的文字***  
~~这是加删除线的文字~~  

# 三、引用
在引用的文字前加>即可。引用也可以嵌套，如加两个>>三个>>>...  
实例：
>这是引用的内容
>>这是引用的内容
>>>>这是引用的内容


# 四、分割线  
三个或者三个以上的 - 或者 * 都可以。  
实例：  
---
------
****

# 五、图片
语法：  
![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加  

实例：  
![江南水乡]（http://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=%E5%9B%BE%E7%89%87&step_word=&hs=0&pn=6&spn=0&di=148390&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=0&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=undefined&cs=2393084083%2C140359889&os=828107738%2C426045215&simid=3526479658%2C575668954&adpicid=0&lpn=0&ln=1716&fr=&fmq=1546493961437_R&fm=&ic=undefined&s=undefined&hd=undefined&latest=undefined&copyright=undefined&se=&sme=&tab=0&width=undefined&height=undefined&face=undefined&ist=&jit=&cg=&bdtype=0&oriquery=&objurl=http%3A%2F%2Fpic29.nipic.com%2F20130519%2F10971173_181903584155_2.jpg&fromurl=ippr_z2C%24qAzdH3FAzdH3Fooo_z%26e3Bgtrtv_z%26e3Bv54AzdH3Ffi5oAzdH3F8AzdH3F09AzdH3Fb88db8lhnmwdc9av_z%26e3Bip4s&gsm=0&rpstart=0&rpnum=0&islist=&querylist=&force=undefined）

# 六、超链接
语法:  
[超链接名](超链接地址 "超链接title")
title可加可不加

[百度](https://www.baidu.com)  
[简书](https://www.jianshu.com)


