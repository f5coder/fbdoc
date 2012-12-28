#MarkDown学习笔记
##概述
###兼容HTML
    <table>
        <tr>
            <td>Foo</td>
        </tr>
    </table>
<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

##区块元素
###列表

    *   列表1
    *   列表2
    *   ....  
*   列表1
*   列表2
*   ....  

###列表下多段落  
    1.  This is a list item with two paragraphs. Lorem ipsum dolor
        sit amet, consectetuer adipiscing elit. Aliquam hendrerit
        mi posuere lectus.
    
        Vestibulum enim wisi, viverra nec, fringilla in, laoreet
        vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
        sit amet velit.

    2.  Suspendisse id sem consectetuer libero luctus adipiscing.  
1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.  

###引用  
    >   This is a list item with two paragraphs. Lorem ipsum dolor
        sit amet, consectetuer adipiscing elit. Aliquam hendrerit
        mi posuere lectus.

    >   Vestibulum enim wisi, viverra nec, fringilla in, laoreet
        vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
        sit amet velit.

    >   Suspendisse id sem consectetuer libero luctus adipiscing.  

>   This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

>   Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

>   Suspendisse id sem consectetuer libero luctus adipiscing.  

###列表下引用
    1.  A list item with a blockquote:
    
        > This is a blockquote
        > inside a list item.

1.  A list item with a blockquote:

    > This is a blockquote
    > inside a list item.


###代码块
        public static void main(){
            System.out.println("Hello,world!");
        }
    
        1.说明
        2.建议    

<br/>

    public static void main(){
        System.out.println("Hello,world!");
    }

    1.说明
    2.建议

###分割线
    ————————————————
————————————————

##区段元素

###强调&特殊字符自动转换
    Whit is this?This is a **BiMoYun.com**.  
Whit is this?This is a **BiMoYun.com**.  

    Whit is this?This is a **&copy;BiMoYun.com**.  
Whit is this?This is a **&copy;BiMoYun.com**.  

    Whit is this?This is a **BiMoYun.com&trade;**.  
Whit is this?This is a **BiMoYun.com&trade;**. 

    Whit is this?This is a *BiMoYun.com&reg;*.
Whit is this?This is a *BiMoYun.com&reg;*.

###链接
####行内式
    让我们到[百度](http://www.baidu.com/ "百度")去吧!.  
让我们到[百度](http://www.baidu.com/ "百度")去吧!.
####参考式
    [baidulink]: http://www.baidu.com/  "去百度"
    让我们到[百度] [baidulink]去吧!.
[baidulink]: http://www.baidu.com/  "去百度"
让我们到[百度] [baidulink]去吧!.
###图片
####行内式
    ![Alt text](/path/to/img.jpg "优质图片")  
![示例图片](/path/to/img.jpg "优质图片")
####参考式
    ![图片不存在][imgSampleLink]
    [imgSampleLink]: url/to/image  "优质图片"
![示例图片][imgSampleLink]
[imgSampleLink]: url/to/image  "优质图片"

###段内代码
    让我们使用`$.ajax()`吧。  
让我们使用`$.ajax()`吧。

##其他
###自动链接
####URL链接
    <http://www.baidu.com/>
<http://www.baidu.com/>
####Email链接
    <bimoyun@gmail.com>
<bimoyun@gmail.com>
###反斜杠
    \*literal asterisks\*
\*literal asterisks\*  

Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号:  

    \   反斜线  
    `   反引号
    *   星号
    _   底线
    {}  花括号
    []  方括号
    ()  括弧
    #   井字号
    +   加号
    -   减号
    .   英文句点
    !   惊叹号



