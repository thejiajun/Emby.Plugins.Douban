# Emby.Plugins.Douban

> 这是 [AlifeLine/Emby.Plugins.Douban](https://github.com/AlifeLine/Emby.Plugins.Douban) 的个人维护分支。
> 上游 2021 年后停更，豆瓣此后开始拒绝自称 App 6.x 的请求，返回「客户端版本过低，请更新」（code 368226），
> 插件八个内置身份里有六个是 6.x，于是约四分之三的刮削请求失败。本分支把它们全部改为 7.x。
> 插件下载见[本仓库的 Releases](https://github.com/thejiajun/Emby.Plugins.Douban/releases)；打 `v*` 标签即自动构建发布。

# Emby豆瓣削刮器
本项目是[jellyfin-plugin-douban](https://github.com/Libitum/jellyfin-plugin-douban) 的Emby版本
使用方法一致
安装方法为
- [点击这里下载最新的插件文件](https://github.com/AlifeLine/Emby.Plugins.Douban/releases)，解压出里面的 **Emby.Plugins.Douban.dll** 文件，通过ssh等方式拷贝到 Emby 的插件目录
- 常见的插件目录如下：
  - 群晖
    - /volume1/Emby/plugins
    - /var/packages/EmbyServer/var/plugins
    - /volume1/@appdata/EmbyServer/plugins
  - Windows
    - emby\programdata\plugins
- 需要**重启Emby服务**，插件才生效。
