# Mesh组网环境指向协议

**请求URL**

```
http://device.isuke.com.cn:6012/server/mesh/getDestination
```

**请求类型**

**请求类型**

POST	Content-Type: application/x-www-form-urlencoded

**请求参数**

| 参数名 | 参数类型 | 是否必填 | 参数说明  |
| ------ | -------- | -------- | --------- |
| mac    | String   | 是       | 设备mac号 |



**返回参数**

| 返回   参数 | 数据类型 | 描述                                                  |
| ----------- | -------- | ----------------------------------------------------- |
| httpHost    | String   | http的前缀地址，如  114.116.49.249:38888              |
| mqttHost    | String   | mqtt的前缀地址,  如 124.71.11.151:1888 (账号密码固定) |