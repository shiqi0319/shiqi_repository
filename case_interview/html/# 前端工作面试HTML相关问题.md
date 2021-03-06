# 前端工作面试HTML相关问题

1. doctype(文档类型)的作用是什么？

> * 对文档进行有效性验证
>>
>>> 它告诉用户代理和校验器这个文档是按照什么DTD 写的。这个动作是被动的，每次页面加载时，浏览器并不会下载DTD 并检查合法性，只有当手动校验页面时才启用。
>
> * 决定浏览器的呈现模式
>>
>>> 对于实际操作，通知浏览器读取文档时用哪种解析算法。如果没有写，则浏览器则根据自身的规则对代码进行解析，可能会严重影响HTML 排版布局。浏览器有三种方式解析HTML文档。
>>>
>>> * 非怪异（标准）模式
>>> * 怪异模式
>>> * 部分怪异（近乎标准）模式

关于IE浏览器的文档模式，浏览器模式，严格模式，怪异模式，DOCTYPE标签，可详细阅读模式标准的内容.

2. 浏览器标准模式和怪异模式之间的区别是什么？
