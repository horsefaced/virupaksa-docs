# virupaksa

数据采集的统一调度平台

## 更新日志

### 2022.05.24

1. 产量文档
   1. 大华安检系统添加液态检测器的设备类型

### 2022.05.23

1. 事件文档
   1. 液体检测报警事件中容器类型添加未知类型
2. 项目与标识对应表
   1. 千佛山医院添加关于打架斗殴部分的说明

### 2022.05.17

1. 事件文档
   1. 添加液体检测报警事件

### 2022.03.23

1. 常量文档
   1. 添加报警等级
   2. 添加处理状态
2. 命令文档
   1. 添加安检门报警数量统计
   2. 添加安检门过人数量统计
3. 更新系统与命令对照表
   1. 更新安检系统的命令与事件部分
   2. 更新项目部分有关安检的注意事项, 见千佛山项目4至7点.
4. 事件部分
   1. 添加安检门过人数量通知

### 2022.03.22

1. 事件文档
   1. 添加安检机报警事件
   2. 添加安检门报警事件

### 2022.03.21

1. 常量文档
   1. 厂家列表添加大华安检系统标识
   2. 其他常量中添加安检包裹大类(大华安检系统 dh-scs)
   3. 设备大类与设备类型添加大华安检系统说明

2. 命令文档
   1. 添加得到安检包裹数量统计
   2. 添加得到安检违禁包裹数量统计
   3. 添加得到安检包裹检测安全率统计
   4. 添加得到安检包裹大类统计
   5. 添加得到安检事件处理率统计

3. 系统与命令对应表添加安检部分
4. 项目与标识对应表千佛山医院部分添加安检系统标识

### 2022.01.06

1. 项目与标识对应表上海电力添加消防部分

### 2021.11.09

1. 常量文档添加开门类型大类, 现包括大华H8900、海康OpenAPI、大华OpenICC

### 2021.11.07

1. 常量文档添加大华openICC的设备大类、设备类型与设备单元类型说明

### 2021.11.04

1. 命令文档添加得到巡更班次记录与巡更班次的点位记录
2. 命令文档中得到巡更路线统计信息部分添加正常巡更次数与异常巡更次数字段

### 2021.11.04

1. 命令文档添加得到巡更统计信息命令
2. 项目与标识对应表千佛山添加巡更系统

### 2021.10.12

1. 项目与标识对应表添加宁夏环保的说明.

### 2021.08.31

1. 常量文档中设备报警分类下的海康威视openapi添加报警分类
2. 常量文档中设备报警分类下的海康威视openapi添加可视对讲的报警类型

### 2021.08.27

事件文档刷卡事件的健康码添加非红、黄、绿范围内的未知类型处理说明

### 2021.08.24

项目与标识对应表中千佛山项目部分添加一键报警说明, 添加消防水压监控系统说明s

### 2021.08.04

项目与标识对应表中千佛山项目添加部分说明

### 2021.07.22

1. 常量文档
   1. 添加海康威视的设备报警类型
2. 项目与标识对应表添加千佛山医院项目

### 2021.07.19

1. 事件文档
   1. 刷卡事件、考勤事件、人脸检测事件、人脸识别事件添加人体体温及是否超温字段
   2. 添加 humanTemperatureAlarm 人体体温报警事件

### 2021.07.16

1. 常量文档添加智菱环境监测系统
2. 常量文档添加智菱环境监测系统设备类型
3. 常量文档bacPresentValue部分添加表面温度、气压、PM10、噪声、信号强度、信号强度指示
4. 项目与标识对应表昙华林部分添加环境监测系统说明

### 2021.06.15

1. 招商银行杭州分行接口添加空气质量概况命令
2. 系统与命令对应表添加空气质量系统部分
3. 常量文档厂商列表添加中广控空气控制系统

### 2021.05.26

1. 常量文档 bacPresentValue 描述部分添加 music 状态, 描述设备当前在播放的音乐

### 2021.05.23

1. 命令文档中修改可视对讲开门命令参数
2. 招商银行杭州分行接口统一PC端接口文档格式

### 2021.05.08

1. 命令文档
   1. 添加根据人员编号得到账户余额
2. 招商银行杭州分行接口
   1. 添加根据人员编号得到账户余额

### 2021.05.08

1. 系统与命令对应表: 消防系统添加getAllDevices命令
2. 常量文档的消防设备类型中添加 113: 消防广播
3. 修正一些文档格式问题

### 2021.05.06

1. 招商银行杭州分行接口:
   1. 添加得到食堂历史人流的命令.
2. 事件文档:
   1. 修正无线接入控制系统信息更新事件说明中的拼写错误
   2. 添加智能厕所数据信息
3. 常量文档:
   1. 添加智能厕所设备分类
4. 更新项目与标识对应表, 添加昙华林的智能厕所说明

### 2021.04.30

1. 事件文档:
   1. 修改无线访问接收点信息更新事件
   2. 修改无线接入控制系统信息更新事件

### 2021.04.26

1. 招商银行杭州分行的食堂人流命令及事件回传的数值从拥堵指数改为五分钟人流数

### 2021.04.23

1. 命令文档添加得到区域中场景以及设置区域场景的命令
2. 命令文档中修改开门、关门、常开、常关四个命令的调用参数
3. 项目标识对应表完善招商银行几个未提供的功能标识

### 2021.04.18

1. 添加招商银行分行接口
   1. 接口提供手机App端接口
   2. 接口提供PC端消费统计和停车场事件推送

### 2021.04.16

1. ITC会议系统设备类型添加投影仪
2. 添加项目定制的文档说明

### 2021.04.14

1. 得到会议: getMeetings 返回中的agenda改为agendas

### 2021.04.13

项目与标识文档中招商银行手机端全部改为暂未提供

### 2021.04.12

1. 命令文档
   1. 考勤统计添加可根据人员名称查询的功能

### 2021.04.11

项目与标识文档添加武汉昙华林、深圳龙华观澜学校

### 2021.04.10

1. 命令文档中查询消费流水命令参数添加员工编号
2. 命令文档中查询消费流水命令返回数据添加员工编号
3. 添加项目与标识文档

### 2021.04.09

1. 常量文档添加考勤签入签出类型定义
2. 命令文档添加得到考勤纪录与得到考勤刷卡纪录命令

### 2021.04.07 15:22

1. 常量文档H8900报警类型添加 8: ‘GIS报警’

### 2021.04.06 10:15

1. 常量文档
   1. 厂家列表添加深信服网络管理系统: { sdk: { manufacturer: 'sangfor', platform: 'wac-snmp' }}
   2. 设备类型添加深信服网络设备
2. 系统与命令对应表
   1. 添加无线管理系统
3. 事件文档
   1. 添加无线接入控制系统信息更新
   2. 无线访问接收点信息更新

### 2021.03.29 19:45

1. 命令文档与事件文档中的消费流水部分添加消费类型为 -1 的其它消费类型.

### 2021.03.24 15:30

1. 常量文档
   1. 厂家列表添加西门子楼宇控制系统 {sdk: {manufacturer: 'siemens', platform: 'bas-opc'}}
   2. 设备类型添加西门子楼控系统设备说明, 现阶段只有 ERV 全热交换器
   3. 其它常量中的bacPresentValue添加 wind_speed, key_locked 说明
2. 系统与命令对应表
   1. 暖通部分添加西门子楼控系统
   2. 暖通部分添加basControl控制命令与deviceOnlineStatusChange事件
3. 命令文档
   1. 添加 basControl 命令说明

### 2021.03.22 17:24

1. 常量文档U8000部分添加摄像头故障报警说明
2. 常量文档U8000部分更改设备类型说明出错的问题

### 2021.03.11 11:22

1. 命令文档添加得到考勤统计数据命令
2. 系统与命令对应表添加考勤系统说明

### 2021.03.11 07:00

1. 常量文档
   1. 厂家列表添加大华u8000系统 { sdk: { manufacturer: 'dahua', platform: 'u8000'}}
   2. 添加大华u8000的设备大类与设备类型
   3. 添加大华u8000的报警类型
2. 系统与命令对应表
   1. 安防系统部分添加大华u8000支持的命令与事件信息

###  2021.01.20 10:03

1. 常量文档添加性别定义

### 2021.01.16 14:43

1. 命令文档
   1. 音乐列表接口添加使用说明

### 2021.01.13 11:15:17

1. 命令文档
   1. 添加得到音乐列表、播放音乐、设置音量、停止音乐播放命令
2. 常量文档
   1. bacPresentValue 添加音量、通用状态标识
   2. 添加迪士普的设备类型与设备报警类型
   3. 添加现阶段厂家列表
3. 系统与命令对应表添加新的音乐广播系统和新的厂家{ sdk: {   manufacturer: 'dsppa',   platform: 'mag6180'  }}

### 2021.01.12 16:37:18

废弃事件文档中的消防设备状态, 使用deviceAlarm设备报警代替.

### 2021.01.06 09:18:00

常量文档中关于lifesmart的设备大类与设备类型修改为数字型.

### 2021.01.05 15:09:59

1. 常量文档
   1. bacPresentValue添加目标温度、 电池电量、用电量、门状态、电压、打开百分比、目标打开百分比、空调模式、空调风量
   2. bacPresentValue修改原表示电量的power 为功率
   3. lifesmart系统设备大类与设备类型添加智慧中心与区域
2. 事件文档
   1. bacPresentValue添加deviceCode
   2. bacAlarm添加deviceCode
3. 系统与命令对应表添加新的系统: { sdk: { manufacturer: 'lifesmart', platform: 'lgc'} }

### 2020.12.22

1. 常量文档添加海康威视的设备类型
2. 系统与命令对应表文档
   1. 安防系统部分添加海康威视及其支持的命令
   2. 视频服务部分添加海康威视及其支持的命令
3. 命令文档中
   1. 视频流和回放流, 在请求中添加deviceCode参数, 现在本参数暂时还不是强制性的
   2. 控制云台, 在请求中添加deviceId, deviceCode参数
   3. 控制镜头, 在请求中添加deviceId, deviceCode参数
   4. 云台快速定位,, 在请求中添加deviceId, deviceCode参数
   5. 锁定云台, 在请求中添加deviceId, deviceCode参数
   6. 云台灯光控制, 在请求中添加deviceId, deviceCode参数
   7. 云台雨刷控制, 在请求中添加deviceId, deviceCode参数
   8. 相机红外控制, 在请求中添加deviceId, deviceCode参数
4. 去除 设备定位的问题中 平台+通道号 规则

## 特别说明

### 关于设备定位的问题

2. 有设备编号 使用 平台 + 设备编号
3. 有设备ID 使用 平台 + 设备ID 


三个定位方式的优先级是： 设备编号 > 设备ID

### 关于频道主题的问题

在MQTT规范中，主题分割符为“/”。但在实践过程中，[nodejs mqtt](https://github.com/mqttjs/MQTT.js) 库以及 [.net mqtt](https://github.com/chkr1011/MQTTnet) 库都支持以“.“为主题分割符，但是 Java 上的一些库是不支持的，必须要使用“/”作为主题分割符，这点请对接人员根据自己使用的MQTT库的规范来。文档中使用“.“作为主题分割符。		 在MQTT规范中，主题分割符为“/”。但在实践过程中，[nodejs mqtt](https://github.com/mqttjs/MQTT.js) 库以及 [.net mqtt](https://github.com/chkr1011/MQTTnet) 库都支持以“.“为主题分割符，但是 Java 上的一些库是不支持的，必须要使用“/”作为主题分割符，这点请对接人员根据自己使用的MQTT库的规范来。文档中使用“.“作为主题分割符。

## 系统与命令对应表

参考[系统与命令对应表](SYSTEM_COMMAND_EVENT_LIST.md)

## 命令接口

参考[命令接口文档](COMMAND_README.md)

## 事件部分

参考[事件文档](EVENT_README.md)

## 常量定义说明

参考[常量的说明](CONSTANTS_README.md)

## 项目与标识对应表

参考[项目与标识对应表](PROJECT_PROVIDER_INFO.md)

