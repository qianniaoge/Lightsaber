# Lightsaber
信息收集，超链接爬取，联动burp，xray，内置afrog，内网主机存活检测，端口检测，弱口令探测，自动生成html模版

<img width="370" alt="image" src="https://user-images.githubusercontent.com/61389299/170186770-69a7cfb8-6ffa-4530-844d-539a8f652ac6.png">

<img width="600" alt="image" src="https://user-images.githubusercontent.com/61389299/170186842-01e0ebe9-3822-4003-8670-c263898b3868.png">

<img width="592" alt="image" src="https://user-images.githubusercontent.com/61389299/170186939-0a7c01f2-5793-4d10-98a1-0b1076f741b6.png">

加上 -open=true 参数就可以运行结束后自动打开html文件 linux需要有firefox浏览器的支持

<img width="523" alt="image" src="https://user-images.githubusercontent.com/61389299/170187315-035f2a62-aad8-4650-a463-ca93838addba.png">

<img width="589" alt="image" src="https://user-images.githubusercontent.com/61389299/170187377-c8005ca7-f756-4499-a205-9fe0332c1516.png">
加上 -link=true 后就会爬取链接的超链接 默认最大爬取时间为30秒 可以通过 -time 参数来更改

<img width="593" alt="image" src="https://user-images.githubusercontent.com/61389299/170187662-cf893d52-c1f7-4154-9920-c28e9cbec9d2.png">
参数 -intranet 可以自动进行内网主机存活探测，端口检测，弱口令探测

<img width="591" alt="image" src="https://user-images.githubusercontent.com/61389299/170187842-a212ca23-0e80-4d5e-b1f3-4f662a2bda1b.png">
也可以直接指定内网ip地址直接进行端口扫描和弱口令探测

<img width="176" alt="image" src="https://user-images.githubusercontent.com/61389299/170188000-807af22e-493f-4188-9fab-fa5b6e9715e8.png">
编辑txt文本内容为 www.baidu.com 和 https://www.baidu.com/

<img width="591" alt="image" src="https://user-images.githubusercontent.com/61389299/170188109-69c8a800-4f5a-45c2-9a1f-cdbf285b8d28.png">
即可自动对文本内网址进行链接爬取端口扫描ip地址获取

<img width="583" alt="image" src="https://user-images.githubusercontent.com/61389299/170188502-fb2f7027-aaf8-4853-ad19-24934421e1bf.png">
参数 -name 即可设置保存文件名称
<img width="1040" alt="image" src="https://user-images.githubusercontent.com/61389299/170188572-e09dddc5-f965-40e4-a781-4094c1cce00e.png">

<img width="590" alt="image" src="https://user-images.githubusercontent.com/61389299/170191856-a8620103-d5d2-4923-9720-359071ec6abb.png">
参数 -a=true 即可在链接爬取结束后进行POC验证工具为afrog

<img width="752" alt="image" src="https://user-images.githubusercontent.com/61389299/170188945-86cf7533-1fdc-451c-8373-9b4f6c48130e.png">
<img width="1614" alt="image" src="https://user-images.githubusercontent.com/61389299/170188979-2d6aa3b4-ac48-4b85-baaf-59fd0e65e6b3.png">
<img width="763" alt="image" src="https://user-images.githubusercontent.com/61389299/170189052-180ce184-b6c0-48a3-9521-7bf7f47990a9.png">

最后的 -server 参数是在vps上操作的话会在vps上开启8080端口，即可通过ip:8080端口访问查看运行结果
<img width="590" alt="WechatIMG12" src="https://user-images.githubusercontent.com/61389299/170189540-a0db85e9-ef07-4867-a746-78d1f0a575a6.png">


同时感谢  https://github.com/zan8in/afrog
         https://github.com/jpillora/icmpscan
         https://github.com/k8gege/LadonGo
的开源项目



