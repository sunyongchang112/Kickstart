# Kickstart
    使用Kickstart或Cobbler批量安装操作系统时的ks文件，实现自动配置静态IP。Flt的ks文件是在批量安装服务器时实现双网卡bond和一些系统参数的调优，实际环境使用时服务端url、分区的格式、IP的配置都需自定义配置，可在%post %end之间添加自定义脚本实现系统设置的初始化。
