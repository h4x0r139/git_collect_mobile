# git_collect_mobile

[toc]

个人收集的移动开发项目，使用git submodule方式，引用已有项目。包含：Android、Flutter、iOS等


# 环境与使用

submodule的使用、git拉取常见问题 参考：[使用submodle及相关问题.md](https://github.com/h4x0r139/git_collect_note/blob/master/doc/%E4%BD%BF%E7%94%A8submodle%E5%8F%8A%E7%9B%B8%E5%85%B3%E9%97%AE%E9%A2%98.md)


文件目录

1. [01_Google](01_Google)：Google 官方项目



# 项目列表

```
git submodule init
git submodule add git@github.com:android/architecture-samples.git 01_Google/architecture-samples
git submodule add git@github.com:android/sunflower.git 01_Google/sunflower
git submodule add git@github.com:android/compose-samples.git 01_Google/compose
git submodule add git@github.com:android/user-interface-samples.git 01_Google/user-interface-samples
git submodule add git@github.com:googlecodelabs/android-testing.git 01_Google/android-testing
git submodule add git@github.com:android/testing-samples.git 01_Google/android-testing-samples
```



## 01_Google



### [architecture-samples](https://github.com/android/architecture-samples)：不同架构实现的demo

- starred：40.2k，Google Android 官方推荐的架构示例



### [sunflower](https://github.com/android/sunflower/)： Jetpack最佳实践demo

- starred：15.4k；Android Jetpack最佳实践demo
- A gardening app illustrating Android development best practices with Android Jetpack.



### [compose](https://github.com/android/compose-samples)：compose-samples

1. Crane
1. JetNews
1. Jetcaster
1. Jetchat
1. Jetsnack
1. Jetsurvey
1. Owl
8. Rally



### [user-interface-samples](https://github.com/android/user-interface-samples)：Android User Interface Samples Repository

1. AppWidget
2. DragAndDrop
3. EmojiCompat
4. Haptics
5. ImmersiveMode
6. People
7. Preferences
8. SplashScreen
9. WindowInsetsAnimation
10. WindowManager



### [android-testing](https://github.com/googlecodelabs/android-testing)：Android（单元）测试

构建有效的单元测试 ：https://developer.android.com/training/testing/unit-testing/

1. Advanced Android in Kotlin 05.1: Testing Basics：https://developer.android.com/codelabs/advanced-android-kotlin-training-testing-basics?hl=zh-cn#2
2. https://github.com/googlecodelabs/android-testing



### [android/testing-samples](https://github.com/android/testing-samples)：在Android平台上测试应用示例

在Android平台上测试应用：https://developer.android.com/training/testing?hl=zh-cn

- espresso 使用：https://developer.android.com/training/testing/espresso?hl=zh-cn

- codelab：https://developer.android.com/codelabs/advanced-android-kotlin-training-testing-basics?hl=zh-cn#0
