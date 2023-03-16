# SSRF
SSRF插件
# 使用方法
把DnsLog地址复制进去就行
![1678951272118](https://user-images.githubusercontent.com/56025844/225543230-fc7534ef-9fc9-4ae7-9e70-dad92ccc248b.png)
如果检测到，可能有SSRF漏洞，则会直接捕获并修改请求包。可直接开启该插件，然后有空就去看看dnslog有无记录，若有记录，可通过对比时间查看具体对应的请求包，然后进行后续测试
