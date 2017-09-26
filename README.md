# Description
Udn NewMedia 常用共通 code

# How to use
```bash
npm install udn-newmedia-utils
```

```js
import Utils from 'udn-newmedia-utils'
```

# API

### Utils.detectMob()
判斷目前使用者瀏覽器為 PC or Mobile
* true  : mobile
* false : pc

### Utils.detectPlatform()
判斷目前使用者瀏覽器為 PC or Mobile 回傳string for GA
* 'Mob' : mobile
* 'PC   : PC

### Utils.detectIE()
判斷目前使用者瀏覽器是否為 IE
* true  : IE
* false : other

### Utils.iOSVersion(Version)
判斷使用者ios 版本 是否大於 Version 主要for video auto play
* true  : 使用者版本 >= 指定 version
* false : 使用者版本 < 指定 version

### Utils.isFacebookApp()
判斷是否為 FB app
* true  : 是 FB app
* false : 否
