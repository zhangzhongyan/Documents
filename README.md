


# Document

用于存放图片文件

# Pods验证

#### 本地验证：
pod lib lint

#### 远程验证准备：
podspec版本、xcode工程版本

#### 推送公有仓库：
##### 注册设备
在向cocoapods远程仓库提交自己的podspec，需要进行设备注册（认证）。

```
pod trunk register xxx@xxx.com 'my name' --description='my macbook air'
```
然后查看自己的邮件，复制邮件中的链接，用浏览器打开即可。（此操作可能出现失败，需良好的网络环境）

##### 提交.podspec
```
pod trunk push FSAttributedString.podspec
```
注意命令执行的目录，需要项目根目录执行。



