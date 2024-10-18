## @telegram/ui 更新记录

## 1.0.0-rc.8

### Patch Changes

- `[Feat]:` 新增加入频道、群组函数 `joinChannel、joinGroup`

## 1.0.0-rc.7

### Patch Changes

- `[Pref]:` `tonConfig.manifestUrl` 设置默认值且不会被替换 `https://xxxxx/tonconnect-manifest.json`
- `[Pref]:` `WebApp.initData` 没有数据时尝试读取浏览器参数携带的 `initData`

## 1.0.0-rc.6

### Patch Changes

- `[Fixed]:` 修复 `token` 为 `undefined` 时 `ws` 也会进行连接
- `[Fixed]:` 修复登录始终返回错误
- `[Pref]:` `Stars` 显示价格向上取整
- `[Feat]:` `debug` 情况下显示 `vConsole`

## 1.0.0-rc.5

### Patch Changes

- `[Feat]:` 添加支付状态弹窗

## 1.0.0-rc.4

### Patch Changes

- - `[Pref]:` 废弃 `sendHeat` ，删除本地缓存时间。
  - `[Feat]:` 添加 `WebSocket` 连接

## 1.0.0-rc.3

- `[Fix]:`
- - 添加 `Stars` 支付数量整数校验
- - `Stars` 支付按钮不会显示

## 1.0.0-rc.2

- `[Fix]:` 修复档位支付，逻辑错误
- `[Feat]:` `openPayList` 函数添加参数，可用于接收支付回调

## 1.0.0-rc.1

- `[Feat]:` 补充 USDT 支付方式
- `[Pref]:` `_setTelegramSDKConfig` 函数是否开启 `debug` 由入参属性更改为从接口读取数据

### 1.0.0-rc.0

- `[Feat]:`
- - **新增 `CJS`、`ESM`、`UMD` 版本** ，同时导出 `index.d.ts`
- - 新增 Class `TG_SDK_UI`
- - 新增 `_setTelegramSDKConfig` 函数用于实例化 Class
