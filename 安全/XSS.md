# 跨站脚本攻击(Cross Site Scripting)
跨站脚本攻击(Cross Site Scripting)，缩写为XSS。恶意攻击者往Web页面里插入恶意Script代码，当用户浏览该页之时，嵌入其中Web里面的Script代码会被执行，从而达到恶意攻击用户的目的。

### 原理
1. 攻击者对含有漏洞的服务器发起XSS攻击（注入JS代码）。
2. 诱使受害者打开受到攻击的服务器URL。
3. 受害者在Web浏览器中打开URL，恶意脚本执行。
4. 获取非法信息

### 防御措施
对用户输入内容格式做校验和转义

### 参考文档
[文档](https://blog.csdn.net/is_zhoufeng/article/details/51474820)