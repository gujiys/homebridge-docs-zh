# SmokeSensor(烟雾传感器)

[HAP-NodeJS 地址](https://github.com/KhaosT/HAP-NodeJS/blob/v0.4.50/lib/gen/HomeKitTypes.js#L3343)

必要
---
* `Characteristic.SmokeDetected` 是否检测到烟雾
    * format 数据类型,UINT8
    * maxValue 最大值 1
    * minValue 最小值 0
    * perms 权限 读,通知


非必要 
---

* `Characteristic.StatusActive`  状态,数据(0,1)
* `Characteristic.StatusFault`
* `Characteristic.StatusTampered`
* `Characteristic.StatusLowBattery` 低电量警告,数据(0,1)
* `Characteristic.Name` 名称