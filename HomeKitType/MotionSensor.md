# MotionSensor (人体传感器)

[HAP-NodeJS 地址](https://github.com/KhaosT/HAP-NodeJS/blob/v0.4.50/lib/gen/HomeKitTypes.js#L3218)

必要
---
* `Characteristic.MotionDetected` 光照强度, 有人为:`true`,没人为:`false`
    * format 数据类型,bool
    * perms 权限 读,通知

非必要 
---

* `Characteristic.StatusActive`  状态,数据(0,1)
* `Characteristic.StatusFault`
* `Characteristic.StatusTampered`
* `Characteristic.StatusLowBattery` 低电量警告,数据(0,1)
* `Characteristic.Name` 名称