# 黑群晖操作计划

## 购买硬件
 - 暴风酷播云
 - 机械硬盘 4t
 - u盘(用来作为引导启动)

## 洗白操作
 - sn/mac地址收集

## 主板升级
 - doc刷mac教程：(资源百度网盘), 使用上面收集到的 mac 地址来进行刷写
```shell
http://www.u-share.cn/forum.php?mod=viewthread&tid=23418&extra=&page=1
```
 - 升级 bios
    > 1. 如果开机进入 bios 后有密码，需拆机拆主板电池清除 bios 密码
    > 2. 查看 bios 的版本号，然后根据官网的升级教程来升级，注意版本号之间的升级顺序
    > 3. 下载相对应的 bios 文件至 u 盘，插入主板进入 bios 进行选择升级
 - bios 下载地址
 ```shell
http://www.asrock.com/mb/Intel/J3455-ITX/index.cn.asp?cat=Download&os=All
 ```

## 系统安装
 - 系统版本选择
    > 1. j3455 主板对应 群晖 ds918+, 所以系统和引导的版本选择相对应机型的
 - 启动盘制作
```shell
https://www.nas2x.com/threads/dsm-6-2-1-20190221.29/
```

 - 启动盘固件下载
```shell
https://xpenology.com/forum/topic/12952-dsm-62-loader/
```

 - 安装系统
```shell
https://post.m.smzdm.com/p/and2km63/
```

 - 系统镜像下载(官方镜像地址)
```shell
https://archive.synology.com/download/DSM/release/
```
## 硬件改装
 - 思路
     >1u 电源的风扇噪音太大，另外机箱风扇的质量也不怎么样，先把电源全部更换了，再看看机箱风扇的效果；如果机箱风尚不给力，则把机箱风扇给更换了。
 - 功耗分析
     > 根据网络上对 j3455 黑群晖功耗的实测，实际不会超过 60w， 所以按照 60w的功耗标准来进行电源采购即可。

## 硬件采购
 - DC-ATX 直插模块
 - 电源适配器
 - 1u 电源转 DC 插口挡板
