# wxbizmsgcrypt
微信数据加解密库 golang


来源　https://github.com/sbzhu/weworkapi_golang/archive/master.zip
xml版本(2019年1月18日更新)

wxbizmsgcrypt.go文件封装了AES加解密过程， 并且实现了VerifyURL, DecryptMsg, EncryptMsg三个接口，分别用于开发者验证接收消息的url、接收消息的解密以及开发者回复消息的加密过程。用户无须关心具体实现。examples/main.go文件提供了如何使用这三个接口的示例。

独立做为仓库发布，以方便项目中直接引用

## 安装方法

    go get github.com/go-laoji/wxbizmsgcrypt
