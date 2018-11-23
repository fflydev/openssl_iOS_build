# openssl_iOS_build
编译好的openssl 支持 armv7 armv7s arm64 x86_64
静态文件在libs
头文件直接使用include

# 编译步骤
编译其他芯片版本，可查看压缩包\Configurations\15-ios.conf
```
./Configure ios-xcrun
make
```
