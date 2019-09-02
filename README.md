# software_test - 软件测试
# 创建一个关于软件测试的新工程：
    idea创建maven工程的方法如博客：https://www.cnblogs.com/Alan0218/articles/10260920.html
# 新项目上传远程git：
    https://www.cnblogs.com/Alan0218/articles/11087185.html
    
    
    
# http - 超文本传输协议
    request请求：由 请求行、请求头、空一行、请求体 四部分组成
        请求行：请求方法+URL(统一资源定位符)+HTTP协议
        请求头：可以由开发自定义需要的请求头信息
    response响应：由 响应状态行、响应头、空一行、响应体 四部分组成



# fiddler抓包工具
    如果遇到fiddler无法抓包情况：请检查浏览器的代理服务器设置处-是否使用了其它代理服务器
    确保fiddler打开时，浏览器代理服务器和fiddler中Connections一致(默认关联ie和Google浏览器，Firefox需要手动设置代理)
    视频教程地址：https://www.bilibili.com/video/av58454086?p=3


	
# fiddler 解决chrome不能抓取https及证书问题？
    https://www.cnblogs.com/Alan0218/articles/10223886.html
       
# fiddler不能导出安全证书
	1,进入fiddler安装目录下：D:\fiddler
	2,执行如下命令：
		makecert.exe -r -ss my -n "CN=DO_NOT_TRUST_FiddlerRoot, O=DO_NOT_TRUST, OU=Created by http://www.fiddler2.com"; -sky signature -eku 1.3.6.1.5.5.7.3.1 -h 1 -cy authority -a sha1 -m 120 -b 09/11/2020
	注意：这个命令最后的日期 09/11/2019 ，一定要大于现在的日期 ，否则创建的证书是过期的





    

