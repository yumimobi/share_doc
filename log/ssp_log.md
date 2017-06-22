日志字段间用\x01分隔， \n为分行符

### SSP开放日志格式
序号|字段|备注
---|---|---
0|日志格式版本|整数，目前为2
1|time stamp|时间戳
2|bid id|竞价 id
3|请求ip|ssp端ip
4|移动设备ip|
5|ssp id|
6|app 名称|
7|app bundle id|
8|app 版本|
9|device model|设备型号
10|device plmn|国家运营商编号
11|adt|是否允许追踪用户数据的标志，0：不允许，1：允许，默认为1
12|connection type|连接类型, 空串表示未知，wifi, 2g, 3g, 4g, ethernet
13|orientation|设备方向, 1：纵向，3：横向
14|android_id|
15|ios_adid|
16|android_adid|
17|local|设备上的本地首选项设置
18|os_type|
19|os_version|
20|screen w|屏幕宽度
21|screen h|屏幕高度
22|screen dpi|屏幕像素密度
23|geo lat|纬度
24|geo lon|经度
25|geo accu|精度
36|ssp protocol version|ssp协议版本
48|ssp is test| 1表示为测试流量，0表示正常流量
51|imei|IMEI码 
52|mac|MAC地址 
53|app id|ssp app id, 由ssp提供
56|appKey| app key
57|brand|手机品牌
58|carrier|运营商 0：移动，1：电信，3：联通，4：unknown
59|inventory_types|淘汰，请忽略
60|device ua|user agent
61|sdk ver|sdk 版本
69|ssp req json|ssp请求json
