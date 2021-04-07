# flutter-gallery
flutter demo演示源码

github地址：https://github.com/flutter/gallery
仓库地址：https://github.com/flutter/gallery.git

clone 项目后，使用 Android Studio、VS Code 或者 IDEA 打开 gallery 项目，此时的 gallery 可能还不能运行，因为这个示例项目是基于最新的 Flutter SDK 开发的，这个 SDK 处于 master 分支，分支上有很多未发布的功能，所以当前的项目不是基于 master 分支的话是编译不过的，

可以使用
flutter channel master
切换到主分支

然后进行SDK升级
flutter upgrade

最后clean一下工程，并重新拉取一下package
flutter pub get

最后找到/lib/main.dart运行主方法即可
