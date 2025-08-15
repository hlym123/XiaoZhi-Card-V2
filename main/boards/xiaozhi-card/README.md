# XiaoZhi Card

* [产品文档](https://docs.m5stack.com/zh_CN/core/Xiaozhi_Card_Kit)

-----------------------------------
## 获取源码

```shell
git clone https://github.com/m5stack/XiaoZhi-Card.git 

cd XiaoZhi-Card

git submodule update --init --recursive 
```

-----------------------------------
## 编译、烧录

* esp-idf veriosn: ESP-IDF v5.4-dirty
 
1. 配置编译目标  

```shell
idf.py set-target esp32s3
```

2. 修改配置

```shell
cp ./main/boards/xiaozhi-card/sdkconfig sdkconfig 
```
 
3. 编译，烧录固件 

> [!NOTE]
> 长按底座按键到灯亮绿色，进入 USB 烧录固件模式。

```shell
idf.py build flash monitor
```

-----------------------------------
## MCP 



------------------------------------
## 功能说明 


