### 一款ionic应用框架，快速生成hybird app 应用

*推送

*扫码

*拍照

*定位

*快速扩展


### 安装步骤

* 下载业务代码
`
git clone https://github.com/yfsoftcom/yf-assister-webapp.git www
`

* 添加手机平台 

#### android
`
ionic platform add android
`

#### ios
`
ionic platform add ios
`

* 添加插件

#### 1.default plugins
`
ionic plugin add cordova-plugin-inappbrowser
`

`
ionic plugin add cordova-plugin-device
`

`
ionic plugin add cordova-plugin-console
`

`
ionic plugin add cordova-plugin-camera
`

`
ionic plugin add cordova-plugin-splashscreen
`

`
ionic plugin add cordova-plugin-whitelist
`

#### 2.AppVersion
`
cordova plugin add https://github.com/whiteoctober/cordova-plugin-app-version.git
`

#### 3.JPush Plugin
`
cordova plugin add https://github.com/jpush/jpush-phonegap-plugin.git --variable API_KEY=[YOUR_APP_ID]
`

#### 4.ionic plugin
`
ionic plugin add ionic-plugin-keyboard
`
#### 5.cordova barcodescanner
`
ionic plugin add https://github.com/phonegap/phonegap-plugin-barcodescanner
`
#### 6.themeablebrowser
`
cordova plugin add cordova-plugin-themeablebrowser
`