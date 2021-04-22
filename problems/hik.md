# 海康接口对接

## http还是https？

查看海康给的文档，确认下是http还是https请求，如果要求使用https，而我们用了http的话，会返回一个html。

{% hint style="danger" %}
 https请求的端口号应当为**443**，否则会报sslError
{% endhint %}



