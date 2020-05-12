# iOS-自动打包脚本
iOS自动打包脚本
上传蒲公英

### 需要修改的地方
*****************************
project_name =  "xx"

project_type = "xcworkspace"

### 蒲公英配置
api_key = "xx"
user_key = "xxx"

### info.plist配置
1.compileBitcode：是否编译bitcode

2.method：
```
app store (打包app store ipa 包)
ad hoc (打包测试上传到fir or 蒲公英包)
enterprise (企业开发中打包)
development (保存一个ipa 单独用于开发或者部署来使用)
```

3.provisioningProfiles：
```
key 为bundle ID  
value 为配置文件的文件名(描述文件名称)
```

# 默认设置
1 会在桌面生成 项目名_build 文件夹
2 文件夹中会有生成的 archive文件和打包好的ipa 文件
3 每次运行都会覆盖掉旧的ipa 文件

