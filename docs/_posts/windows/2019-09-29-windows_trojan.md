---
layout: post
title:  "微软windows电脑Trojan客户端使用教程"
comments: true
categories: windows电脑
---

* content
{:toc}

### 第一步：下载 Trojan 软件并添加Trojan节点

* 点击下载 Trojan Windows客户端：v2rayN
    * <a class="downbtn" href="https://yhvps.com/usr/uploads/app/v2rayN-win-with-trojan-v2.zip" target="_blank" rel="noopener">下载地址1</a>
    * <a class="downbtn" href="https://github.com/go2world/ss/releases/download/0.0.4/v2rayN-win-with-trojan-v2.zip" target="_blank" rel="noopener">下载地址2</a>
    
* 双击打开trojan文件夹下的 v2rayN.exe 文件
    * 如客户端运行Trojan报错，请尝试下载以下软件，安装完毕再运行Trojan
    * <a class="downbtn" href="https://www.microsoft.com/zh-CN/download/details.aspx?id=48145" target="_blank" rel="noopener">Visual C++ 2015 (x64、x86均安装)</a>
    * <a class="downbtn" href="https://support.microsoft.com/zh-cn/help/3151800/the-net-framework-4-6-2-offline-installer-for-windows" target="_blank" rel="noopener">Windows.NET Framework 4.6.2</a>

* 桌面右下角会出现1个小图标，再次双击，打开 Trojan 设置面板
* 点击「服务器」-「Add [Trojan] server」来添加Trojan节点
* ![]({{ '/res/img/win/win1.png' | prepend: site.baseurl  }})
* * *

### 第二步：创建Trojan服务
* 关闭其他代理软件（例如shadowsocks）
* 输入「账号」页面的 Trojan 节点信息  (没有trojan节点在这里购买：<a class="downbtn" href="https://us04.go2world.tk/home/ref/6360407488" target="_blank" rel="noopener">Trojan节点服务提供商</a>)
* 点击「OK」

* ![]({{ '/res/img/win/win2.png' | prepend: site.baseurl  }})
* ![]({{ '/res/img/win/win3.png' | prepend: site.baseurl  }})

*********

### 第三步：启用Trojan服务

* 点击桌面右下角「V」图标
* 点击「启用 Http 代理」
* 选择你想要的「HTTP代理模式」（推荐PAC，可智能分流国内外流量）

* ![]({{ '/res/img/win/win4.png' | prepend: site.baseurl  }})

*********
####  现在，开始享受无界网络吧