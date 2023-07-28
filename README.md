# AirFly
## 机场订阅一键生成ip代理池，让机场起飞！
[release 下载链接](https://github.com/zgao264/AirFly/releases/)
```
   ▄████████  ▄█     ▄████████    ▄████████  ▄█       ▄██   ▄   
  ███    ███ ███    ███    ███   ███    ███ ███       ███   ██▄ 
  ███    ███ ███▌   ███    ███   ███    █▀  ███       ███▄▄▄███ 
  ███    ███ ███▌  ▄███▄▄▄▄██▀  ▄███▄▄▄     ███       ▀▀▀▀▀▀███ 
▀███████████ ███▌ ▀▀███▀▀▀▀▀   ▀▀███▀▀▀     ███       ▄██   ███ 
  ███    ███ ███  ▀███████████   ███        ███       ███   ███ 
  ███    ███ ███    ███    ███   ███        ███▌    ▄ ███   ███ 
  ███    █▀  █▀     ███    ███   ███        █████▄▄██  ▀█████▀  
                    ███    ███              ▀                      version: 0.1
                          
                         机场订阅一键生成ip代理池，让机场起飞！
                                                                https://zgao.top 

Usage: 

- 不带用户名和密码认证的 http、socks5协议 端口（建议本地和内网访问）
airfly -l mixed://:6666 -u "机场订阅链接1" -u "机场订阅链接2"

- 带用户名和密码认证的 http、socks5协议 端口 （建议公网访问）
airfly -l mixed://user:pass@:6666 -u "机场订阅链接1" -u "机场订阅链接2"

协议:
        支持 socks5、http、ss、ssr、trojan、vmess、vless 主流的的科学上网协议

参数：
  -c string
        节点检测健康存活的url (default "http://www.msftconnecttest.com/connecttest.txt#expect=200")
  -ci int
        检测节点健康存活的时间间隔(单位：s) (default 600)
  -ct int
        节点请求的最大超时时间(单位：s) (default 10)
  -l value
        在本地监听的协议端口，支持http、socks5、mixed(http和socks5共用一个端口)
  -s string
        rr: 轮询模式
        ha: 高可用模式
        lha: 基于延迟的高可用性模式 (default "rr")
  -u value
        机场订阅链接
  -v    输出详细日志信息 (default true)
```
