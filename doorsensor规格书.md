# 规格书-门磁探测器

## 供电及电源

|    Syntax    | Description |
| :----------: | :---------- |
|   供电方式   | 干电池      |
|     型号     | 23A         |
|   供电电压   | 12V         |
|   待机电流   | <5uA        |
| 无线发射电流 | <15mA       |

## 无线参数

|    Syntax    | Description                            |
| :----------: | :------------------------------------- |
|   编码方式   | ASK（OOK）                             |
|   无线地址   | 20bit                                  |
|    功能码    | 4bit                                   |
|   震荡电阻   | 330K 可定制                            |
| 无线发射距离 | 空旷 > 120 m                           |
| EV1527 编码  | 内置兼容                               |
| PT2262 编码  | 需定制开发                             |
|   发射频率   | 433.92MHZ<br>（可选 315MHZ,868.32MHZ） |
|   编码方式   | MCU 内部编码                           |

## 主要功能和上报数据说明

|      Syntax      | Description    |     |
| :--------------: | :------------- | :-: |
|   开门数据上报   | 支持           | 5H  |
|   关门数据上报   | 支持（可关闭） | 6H  |
| 电池低压数据上报 | 支持（可关闭） | 7H  |
