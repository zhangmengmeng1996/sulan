# sulan
#### 简介
封装基于Liunx命令grep（fgrep）的日志文件搜索系统。旨在给开发、测试、运维快捷定位线上测试、生产问题。
#### 体验地址
`http://106.13.230.2/sulan/`

#### 目前项目有两个页面
- 应用管理页面 `http://106.13.230.2/sulan/index.html`
![avatar](image/app编辑示意图.png)
- 日志搜索页面 `http://106.13.230.2/sulan/apps.html`
![avatar](image/搜索示意图.png)
>请求日志聚拢，通过一个uuid聚拢一个请求的所有日志.百度搜索日志MDC，在过滤器设置一个UUID。
>微服务日志，通过在起始端服务设置一个日志ID，通过微服务框架过滤器层层下钻传递这个日志ID，达到一个日志ID聚拢各个服务的日志。


- 后续会增加一个结果快照页面