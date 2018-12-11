# NetworkLab1_Server  
华中科技大学计算机网络实验1：Socket编程实现的简易HTTP服务器  
编写一个支持多线程处理的Web服务器软件，要求如下：  		
##第一级：
+可配置Web服务器的监听地址、监听端口和虚拟路径。
+能够单线程处理一个请求。当一个客户（浏览器,输入URL：http://127.0.0.1/index.html）连接时创建一个连接套接字；
+从连接套接字接收http请求报文，并根据请求报文的确定用户请求的网页文件；
+从服务器的文件系统获得请求的文件。 创建一个由请求的文件组成的http响应报文。（报文包含状态行+实体体）。
+经TCP连接向请求的浏览器发送响应，浏览器可以正确显示网页的内容；
+服务可以启动和关闭。
##第二级：
+支持多线程，能够针对每一个新的请求创建新的线程，每个客户请求启动一个线程为该客户服务；
+在服务器端的屏幕上输出每一个请求的来源（IP地址、端口号和HTTP请求命令行）
+支持一定的异常情况处理能力。
##第三级：
+能够传输包含多媒体（如图片）的网页给客户端，并能在客户端正确显示；
+对于无法成功定位文件的请求，根据错误原因，作相应错误提示。
+在服务器端的屏幕上能够输出对每一个请求处理的结果。
+具备完成所需功能的基本图形用户界面（GUI），并具友好性。
