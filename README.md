# AppStorePrivacyInfo
解决部分已经不在维护的SDK的隐私清单问题

## 引入方式 

#### AFNetworking

```
pod 'AFNetworking', :git => 'https://github.com/gzx543097079/AppStorePrivacyInfo.git', :tag => 'AFNetworking-4.0.1'
```

#### PureLayout

```
pod 'PureLayout', :git => 'https://github.com/gzx543097079/AppStorePrivacyInfo.git', :tag => 'PureLayout-3.1.9'
```


#### 另外在Demo中提供了本地集成的方式

<br>
<br>

> 目前测试 苹果审核 只会审核在清单内的，然后  AFNetworking 不包含任何隐私清单，测试不处理 AFNetworking隐私清单问题依旧可以正常上线
另外 这个可以查看这个库里面有本地集成的方式，用来解决不用升级SDK版本就可以解决隐私清单问题，本地集成的方式是否可以通过审核还在测试中
