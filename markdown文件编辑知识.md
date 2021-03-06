# markdown 文本编辑器基本语法  
因为github上.md文件使用较多，所以可以了解下markdow编辑器的基本语法，也相当于多学了一个知识点了  
这是一个markdown基本语法介绍的网页  
https://www.cnblogs.com/yabin/p/6366151.html  
https://www.cnblogs.com/jaesun/p/Markdown-ji-chu-yu-fa.html#%E8%84%9A%E6%B3%A8footnote  
有更好更全的可以贴出来  
## 添加标题（标题字号会比较大且是加粗的）：  
可添加六级标题，用#和空格来表示标题：  
# 标题1“# 标题1”  
## 标题2“## 标题2”  
### 标题3“### 标题3”  
#### 标题4“#### 标题4”  
##### 标题5“##### 标题5”  
###### 标题6“###### 标题6”  
## 换行  
在每行的末尾留两个空格即可换行  `space space`  
## 加粗、斜体  
用\*\* \*\*把内容框起来，**来jia粗我**  
\* \* 把内容框起来，*来xie我鸭*  
## 删除线  
`~~来删除我啊~~`  
~~来删除我啊~~  
<details><summary>三角下拉收缩内容功能</summary>
    
>`<details><summary>XXXXXXX</summary>`作为标题  
与正文空一行  
xxxxx  
`</details>`作为结尾  
</details>   

## 引用文本  
用\>加在文本的前面，必须在行首  
>wo shi yinyong de wenben  
## 用格式来注释文本  
    与标题行相比，进行缩进4个空格的距离  
## 引用代码  
用\` \`，或\`\`\` \`\`\`框起来, 键盘左上角数字1前面的符号  
`int a=3`  
```  
int a=3  
int b=4  
int c=a+b  
```  
\`int a=3\`  
\`\`\`  
int a=3  
int b=4  
int c=a+b  
\`\`\`  
## 添加超链接  
第一种方法: [链接到百度](https://www.baidu.com "百度")  
第二种方法: [还是链接到百度][baidu]  

[baidu]:https://www.baidu.com  
第二种方法的网址链接必须顶格，并且中间需间隔一行，不能添加其他内容  
```
第一种方法: [链接到百度](https://www.baidu.com "百度")  
第二种方法:   
[还是链接到百度][baidu]  

[baidu]:https://www.baidu.com
```
## 分割线---  
---  
*上面是一个分割线,用---*  
## 转义符\\  
类似于C/C++中的转义符\\  
## 层级结构排版  
\*,+,- 和空格，或者数字+‘.’+‘空格’来表示层级  
- 第一层级，用的-  
- 第二层级，用的-  
  1. 2.1层级，用的1.   
  2. 2.2层级，用的2.   
+ 第三层级，用的+   
  * 3.1层级，用的*   
**注意符号后面加的有空格`space`**  
```
- 第一层级，用的-  
- 第二层级，用的-  
  1. 2.1层级，用的1.   
  2. 2.2层级，用的2.   
+ 第三层级，用的+   
  * 3.1层级，用的*   
```  
## 添加表格
```  
第一格表头|第二格表头  
-------|--------  
内容单元格 第一列第一格 | 内容单元格第二列第一格  
内容单元格 第一列第二格 多加文字 | 内容单元格第二列第二格   
```
效果如下： 

第一格表头|第二格表头  
-------|--------  
内容单元格 第一列第一格 | 内容单元格第二列第一格  
内容单元格 第一列第二格 多加文字 | 内容单元格第二列第二格  
## 添加脚注  
**可能由于github的markdown的版本问题，无法实现脚注的功能**  
类似于超链接,脚注链接需要顶格  
>一个具有脚注的文本A。`[^1]`  
[^1]: 的解释A。  
## 添加图片  
首先上传需要添加的图片，通过Upload files按钮添加  
其次点击图片，取得图片的网页地址  
在相应的文档位置按如下方式添加图片  
`命令是这样的: ![图片的注释内容]（图片的网页地址）`  
这里有一个显示图片的教程，https://blog.csdn.net/Cassie_zkq/article/details/79968598  
![显示图片](https://github.com/liaotianyu269/flower-style-learning-group/blob/master/%E5%9B%BE%E4%BE%8B/%E6%8D%95%E8%8E%B7.PNG)  
