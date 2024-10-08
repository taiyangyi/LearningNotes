# 1、Nginx 概述

`Nginx` 的官方网站为：`http://www.nginx.org` ，是由俄罗斯人 `lgor Sysoev (伊戈尔·塞索耶夫)` 于 `2002` 年设计开发，`2004` 年 10 月 4 号首次公开发布，版本号为 `0.1.0`。 

`Nginx` 是一款使用 `C` 语言开发的高性能的 `HTTP` 和 `反向代理` 服务器，同时，它还可以提供 `IMAP/POP3` 代理服务等功能。 在实际使用中，由于 `Nginx` 以其稳定的性能、丰富的功能集、系统资源低消耗逐渐被各大厂商以及开发者认可。官方测试 `Nginx` 能够支支撑5万并发链接，并且 CPU、内存等资源消耗却非常低，运行非常稳定。在国内，比如 字节、阿里、京东等著名厂商都在使用。
 
# 2、Nginx 应用场景

- **HTTP 服务器**，Nginx 是一个 HTTP 服务可以独立提供 HTTP 服务，用来做网页静态服务器

- **虚拟主机**，基于不同端口或者不同域名实现在一台服务器多个网站

- **方向代理、负载均衡**，当网站的访问量达到一定程度，单台服务器不能满足用户的请求时，需要用多台服务器建立集群使用 Nginx做反向代理。并且对请求实现负载按定义规则分配给服务器，不会因为某台服务器负载高而宕机或让某台服务器出现闲置的情况。


# 3、版本介绍
| **版本**|**网址**|
|:------:|:------|
|`Nginx`开源版|http://nginx.org |
|`Nginx plus` 商业版|https://www.nginx.com |
|`Openresty`|http://openresty.org/cn 是一个基于 Nginx 与 Lua 的高性能 Web 平台，其内部集成了大量精良的 Lua 库、第三方模块以及大多数的依赖项|
|`Tengine`|http://tengine.taobao.org 淘宝二开的Nginx。在Nginx的基础上，针对大访问量网站的需求，添加了很多高级功能和特性|

