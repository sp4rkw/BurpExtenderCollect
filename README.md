# BurpExtenderCollect

#### 此项目用于收集渗透测试中，BurpSuite中好用的插件


## 插件介绍

- **chunked-coding-converter** --- Burp suite 分块传输辅助插件 [分块传输原理戳这里](https://xi4or0uji.github.io/2019/11/07/%E5%88%A9%E7%94%A8%E5%88%86%E5%9D%97%E4%BC%A0%E8%BE%93%E7%BB%95%E8%BF%87WAF%E8%BF%9B%E8%A1%8CSQL%E6%B3%A8%E5%85%A5/) 

    [插件地址](https://github.com/c0ny1/chunked-coding-converter)
- **logger++** --- 高亮显示数据包，正则过滤查找需要的数据包，可以随意清理数据包而不用担心丢失重要数据包（burp的http-history还会存在该数据包）

    [插件地址](https://github.com/nccgroup/LoggerPlusPlus)
- **xp_CAPTCHA** --- 图片验证码识别，对于简单图片验证码保护的接口，可以使用此插件结合burp自带爆破功能进行暴力破解,使用说明直接看插件的github说明 

    [插件地址](https://github.com/smxiazi/NEW_xp_CAPTCHA)
- **jsEncrypter** --- 用于前端加密的接口需要进行暴力破解时使用，关于此插件和其使用说明[戳这里](https://gv7.me/articles/2017/jsEncrypter/) 

    [插件地址](https://github.com/c0ny1/jsEncrypter)
- **HaE** --- 用于请求高亮标记与信息提取，正则可自定义，作者也提供了一些好用的规则，保护眼睛，从使用HaE做起QWQ  

    [插件地址](https://github.com/gh0stkey/HaE)
- **Turbo Intruder** --- 用于暴力破解，更快且可根据需求自定义爆破脚本，使用需要一点python编程基础，但插件也自带了一些脚本，可以一键使用，比如race.py可以用于进行条件竞争的漏洞测试  

    [插件地址](https://github.com/PortSwigger/turbo-intruder)
- **burpFakeIP** --- 用于伪造ip的插件，在特定场景下还是挺有用的，便于常规测试  

    [插件地址](https://github.com/TheKingOfDuck/burpFakeIP)
- **WooYun-Payload** --- 通过http请求包中域名，路径，参数等获取乌云历史漏洞中类似的数据，对于新白帽子有一定启发价值  

    [插件地址](https://github.com/boy-hack/wooyun-payload)
- **U2C** --- 用于将burp中的unicode编码转成中文，虽然现在已经不维护了，但是还是可以使用  

    [插件地址](https://github.com/bit4woo/u2c)
- **JSON&HTTPP** --- 用于将json格式数据转换成x=y格式数据，最大的利用场景在于快速测试接口是否隐藏了参数，比如返回包里面的参数  

    [插件地址]()
- **J2EEScan** --- 用于J2EE应用程序的Web应用程序渗透测试扫描，插件使用介绍[戳这里](https://github.com/lilifengcode/Burpsuite-Plugins-Usage/blob/master/Burpsuite%E6%8F%92%E4%BB%B6%E4%B9%8BJ2EEScan%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95.md)  

    [插件地址](https://github.com/ilmila/J2EEScan)
- **Brida** --- 结合frida编写使用加密解密脚本，使用参考[戳这里](https://mp.weixin.qq.com/s?__biz=MzUzODU3ODA0MA==&mid=2247484967&idx=1&sn=1f6aae947fd95e6f7a9e2f0037b522f8&chksm=fad4db30cda352263829d340a6bb5d2ec0477016bb1b48d9536f991396dc65534e05f126b439&cur_album_id=1650939093905702915&scene=190#rd)  

    [插件地址](https://github.com/federicodotta/Brida)
- **param-miner** --- 缓存投毒检测插件，此漏洞的详细解释[戳这里](https://blog.csdn.net/angry_program/article/details/113124854)，工具使用[戳这里](https://www.modb.pro/db/86328)  

    [插件地址](https://github.com/portswigger/param-miner)
- **InQL** --- 渗透测试中可以对GraphQL快速利用，演示视频[戳这里](https://blog.doyensec.com/public/images/inql_demo.mp4)  

    [插件地址](https://github.com/doyensec/inql)
- **Copy As Python-Requests** --- 数据包转换成python 的 requests代码并复制到剪切板，极大的加快需要编写自定义python脚本的速度，使用说明[戳这里](https://www.cnblogs.com/Cl0ud/p/13616665.html)

    [插件地址](https://github.com/silentsignal/burp-requests)
- **Copy Request & Response** --- 快速按规范复制得到请求包/返回包的内容，方便编写渗透测试报告，演示动图[戳这里](https://github.com/CompassSecurity/burp-copy-request-response/blob/master/demo.gif)

    [插件地址](https://github.com/CompassSecurity/burp-copy-request-response)
- **CaA** --- 主要作用就是收集流经BurpSuite Proxy模块中的HTTP流量，并从中提取一些有价值的信息，可以用于接口的枚举。介绍文档直接看官方github[戳这里](https://github.com/gh0stkey/CaA)

    [插件地址](https://github.com/gh0stkey/CaA)
- **EasyBurpVuln** --- 具备自动添加Payload和一定的扫描能力，这个插件最主要的作用是提供基础代码，有助于二次魔改，插件介绍博客[戳这里](https://www.cnblogs.com/donot/p/14911801.html)

    [插件地址](https://github.com/donot-wong/EasyBurpVuln)