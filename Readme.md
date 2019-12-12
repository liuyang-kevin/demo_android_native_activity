# 项目
纯C/C++ 启动的 Android 应用

* manifest中使用使用 `android:name="android.app.NativeActivity"` 基本类型启动Activity
* CMake中使用 `native_app_glue` 黏合NativeActivity与helloworld


# 文章
[步骤来自本文章](https://medium.com/androiddevelopers/getting-started-with-c-and-android-native-activities-2213b402ffff)

# 个人看法
文章最后介绍了使用OpenGL等操作。但c/c++代码终归需要jni.h的加持。除非有要移植的代码。本方式还不要用于生产环境。