iOS源码编译配置流程

环境版本
* mac OS 11.5.2
* Xcode 13.1

Apple开源代码地址：https://opensource.apple.com

点击对应macOS版本，找到对应objc4源码和相关依赖文件，点击右侧下载。

或者去: https://opensource.apple.com/tarballs/ 库名/库名-版本号.tar.gz  下载对应版本号的objc4源码和依赖文件.
例如：https://opensource.apple.com/tarballs/dyld/dyld-852.2.tar.gz


objc4-824
dyld-852.2
Libc-1439.141.1
libclosure-79
libdispatch-1271.120.2
libplatform-254.80.2
libpthread-454.120.2
xnu-7195.141.2

objc4-824在苹果源码里下载不到，有网友曾经下载到过，这里使用的objc4-824是从网友的github里copy的。

让objc能编译运行的过程可以看git commit提交。

参考文章：
[iOS-objc4-781源码编译配置流程](https://www.jianshu.com/p/4f15c551a0ea)
[OC底层系列》- 配置可编译运行的objc4源码](https://www.jianshu.com/p/4a2c8e5518c7)
[OC底层原理-objc818源码编译](https://www.jianshu.com/p/5952c0f5cc1b)
[iOS底层原理01：objc4-818 源码编译](https://www.jianshu.com/p/341be74714e4) 