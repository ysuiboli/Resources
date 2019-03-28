# Resources

## NDK升级问题

```No toolchains found in the NDK toolchains folder for ABI with prefix: mips64el-linux-android```

#### 原因

https://github.com/google/filament/issues/15

google在ndk r17版本删除了mips相关的toolchains文件。

#### 解决方法

自己下载mips64el-linux-android-4.9放到NDK目录下，具体路径：<自己放置路径>/Android/sdk/ndk-bundle/toolchains/

###### mac默认路径：~/Library/Android/sdk/ndk-bundle/toolchains/

[mips64el-linux-android-4.9下载](https://github.com/ysuiboli/Resources/blob/master/mips64el-linux-android-4.9.zip)

---
