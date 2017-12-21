# 目录

## pdf文件夹中：
[Python 爬虫：把廖雪峰的教程转换成 PDF 电子书](./pdf)
这里会遇到htmltopdf的问题
用下面这个方法解决：
https://itaken.github.io/python/2017/02/18/pdfkit%E9%94%99%E8%AF%AF%E8%B0%83%E8%AF%95.html
就是重新下载0.12.4版本的wkhtmltopdf
直接install是不行的

但是会发现廖雪峰网站的反扒太厉害了，一次请求太多就会返回503错误，所以需要用代理尝试

关于代理，可以用
https://github.com/yangtao4389/proxy_pool
这里面的代理池来获取。
直接看read_first文档，进Run中运行main，调用api接口，具体的测试api有use_proxy_pool.py这个文件可以来实现。


## runoob2pdf文件夹中：
爬取的是‘菜鸟教程’里面的内容，直接运行该runoob2pdf.py文件，很快就能生成pdf。暂时没遇到反扒

