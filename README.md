# device_drvFiles描述
 基于STM32HAL库写的常用芯片、设备驱动库

# License
本框架中的所有代码都采用了Apache协议，使用者可以闭源修改后的代码，但是必须保留源自作者的版权声明

# 使用方式
## 文件结构
```
--+ device_drvFiles
    --+ EEPROM
        --- EEPROM_24C02.h
        --- ...
        --- 其他型号设备驱动文件
    --+ FLASH
    --+ ...
    --+ 按类型区分的设备文件夹
```
## 文件说明
- 采用Apache协议开源
- 非超巨大规模设备驱动文件，采用纯C头文件格式
- 头文件格式
  - 权限声明
  - 预编译选项
  - 移植前必修改量定义
  - 其他常量定义
  - 驱动结构定义
  - 驱动函数声明and注释说明
  - 驱动函数详细定义

# 合作开发
欢迎和我一起开发这个STM32HAL设备驱动文件库
- QQ:2373180028
- mail:2373180028@qq.com
- 地址:华中科技大学启明学院6楼