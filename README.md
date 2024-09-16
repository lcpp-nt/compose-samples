# Jetpack Compose 示例（Samples
<img src="readme/samples_montage.gif" alt="Jetpack Compose Samples" width="824" />

本项目fork自Android官方开源项目(https://github.com/android)[android]，更偏向于使用中文注释修改（由于我的英文实在有点差）（This project is forked from the official Android open source project(https://github.com/android)[android]. It is more inclined to use Chinese comments to modify (because my English is really poor).

此代码库包含一组单独的 Android Studio 项目，可帮助您了解 Android 中的 Compose。每个示例都演示了不同的用例、复杂程度和 API。（This repository contains a set of individual Android Studio projects to help you learn about
Compose in Android. Each sample demonstrates different use cases, complexity levels and APIs.

欲了解更多信息，请阅读文档。（For more information, please [read the documentation](https://developer.android.com/jetpack/compose).


💻 要求（Requirements）
------------
要试用这些示例应用，您需要使用Android Studio 。您可以克隆此存储库或按照此处的步骤从 Android Studio 导入项目 。（To try out these sample apps, you need to use [Android Studio](https://developer.android.com/studio).
You can clone this repository or import the
project from Android Studio following the steps
[here](https://developer.android.com/jetpack/compose/setup#sample).

🧬 示例（Samples）
------------

| Project | |
|:-----|---------|
|  <br><img src="readme/jetnews.png" alt="JetNews" width="240"></img> <br><br>示例博客文章查看器演示了如何在典型的 Material 应用和真实架构中使用 Compose。（A sample blog post viewer that demonstrates the use of Compose with a typical Material app and real-world architecture. <br><br> • 中等复杂度（Medium complexity<br>• 多种 UI（Varied UI<br>• 浅色和深色主题（Light & dark themes<br>• 资源加载（Resource loading<br>• UI 测试（UI Testing <br><br> **[> Browse](JetNews/)**<br><br> | <img src="readme/screenshots/JetNews.png" width="320" alt="Jetnews sample demo"> |
|  |  |
|  <br><img src="readme/jetchat.png" alt="Jetchat" width="240"></img> <br><br> 专注于 UI 状态模式和文本输入的示例聊天应用。（A sample chat app that focuses on UI state patterns and text input.<br><br>• 低复杂度（Low complexity<br>• Material Design 3 主题和 Material You 动态颜色（Material Design 3 theme and Material You dynamic color<br>• 资源加载（Resource loading<br>• 返回按钮处理（Back button handling<br>• 与架构组件集成：导航、Fragments、LiveData、ViewModel（Integration with Architecture Components: Navigation, Fragments, LiveData, ViewModel<br>• 动画（Animation<br>• UI 测试（UI Testing<br><br>**[> Browse](Jetchat/)** <br><br> | <img src="readme/screenshots/Jetchat.png" width="320" alt="Jetchat sample demo">|
|  |  |
| <br><img src="readme/jetsnack.png" alt="Jetsnack" width="240"></img> <br><br>Jetsnack 是一款使用 Compose 构建的示例零食订购应用。（Jetsnack is a sample snack ordering app built with Compose.<br><br>• 中等复杂度（Medium complexity<br>• 自定义设计系统（Custom design system<br>• 自定义布局（Custom layouts<br>• 动画（Animation<br><br>**[> Browse](Jetsnack/)** <br><br>  | <img src="readme/screenshots/Jetsnack.png" width="320" alt="Jetsnack sample demo">|
|  |  |
| <br><img src="readme/jetcaster.png" alt="Jetcaster" width="240"></img> <br><br> 示例播客应用具有功能齐全的 Redux 风格架构，并展示了动态主题。（A sample podcast app that features a full-featured, Redux-style architecture and showcases dynamic themes.<br><br>• • 高级示例（Advanced sample<br>• 使用播客插图进行动态主题设计（Dynamic theming using podcast artwork<br>• 图像提取（Image fetching<br>• WindowInsets支持[`WindowInsets`](https://developer.android.com/reference/kotlin/android/view/WindowInsets) support<br>• 协程（Coroutines<br>• 使用 Room 进行本地存储（Local storage with Room<br><br>**[> Browse](Jetcaster/)** <br><br>  | <img src="readme/screenshots/Jetcaster.png" width="320" alt="Jetcaster sample demo">|
|  |  |
| <br><img src="readme/reply.png" alt="Reply" width="240"></img>  <br><br> Reply Material Study 的 Compose 实现，这是一款专注于移动设备、平板电脑和可折叠设备的自适应设计的电子邮件客户端应用。它还展示了全新的 Material Design 3 主题、动态颜色和导航组件。（A compose implementation of the Reply material study, an email client app that focuses on adaptive design for mobile, tablets and foldables. It also showcases brand new Material design 3 theming, dynamic colors and navigation components.<br><br>• 中等复杂度（Medium complexity<br>• 手机、平板电脑和台式机的自适应 UI（Adaptive UI for phones, tablet and desktops<br>• 可折叠设备支持（Foldable support<br>• Material 3 主题和组件（Material 3 theming & Components<br>• 动态颜色和浅色/深色主题支持（Dynamic colors and Light/Dark theme support<br><br>**[> Browse](Reply/)** <br><br>  | <img src="readme/screenshots/Reply.png" width="320" alt="Reply sample demo">|
|  |  |
| <br><img src="readme/jetlagged_heading.png" alt="JetLagged" width="240"></img>  <br><br>睡眠追踪器应用示例，展示如何在 Compose 中创建自定义布局和图形（A sample sleep tracker app, showcasing how to create custom layouts and graphics in Compose<br><br>• 自定义布局（Custom Layouts<br>• 带路径的图形Graphs with Paths<br><br>**[> Browse](JetLagged/)** <br><br>  | <img src="JetLagged/screenshots/JetLagged_Full.png" width="320" alt="JetLagged sample demo">|

🧬 Additional samples
------------

| Project | |
|:-----|---------|
| <br><img src="readme/nia.png" alt="Now in Android" width="240"></img>  <br><br>一款用于了解 Android 最新新闻和发展情况的应用程序。（An app for keeping up to date with the latest news and developments in Android.<br><br>• Jetpack Compose第一个应用程序。（ [Jetpack Compose](https://developer.android.com/jetpack/compose) first app.<br>• 实施推荐的 Android架构指南（Implements the recommended Android [Architecture Guidelines](https://developer.android.com/topic/architecture) <br>• 在真实应用程序环境中全面集成Jetpack 库> 浏览 （Integrates [Jetpack Libraries](https://developer.android.com/jetpack) holistically in the context of a real world app<br><br><a href="https://play.google.com/store/apps/details?id=com.google.samples.apps.nowinandroid"><img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" height="70"></a><br>**[> Browse](https://github.com/android/nowinandroid)** <br><br>  | <img src="readme/screenshots/NiA.png" width="320" alt="Now In Android Github Repository">|
|  |  |
| <br><img src="readme/material_catalog.png" alt="Material Catalog" width="240"></img>  <br><br> Jetpack Compose 中提供的 Material Design 组件和功能目录。了解如何实现它们以及它们在真实设备上的外观和行为。（A catalog of Material Design components and features available in Jetpack Compose. See how to implement them and how they look and behave on real devices.<br><br>• 存在于 AOSP 中 - 始终保持最新（Lives in AOSP—always up to date<br>• 使用与 API 参考文档相同的示例（Uses the same samples as API reference docs<br>• 主题选择器可在运行时更改 Material Theming 值（Theme picker to change Material Theming values at runtime<br>• 指南、文档、源代码和问题跟踪器的链接> 在 AOSP 上浏览（Links to guidelines, docs, source code, and issue tracker<br><br><a href="https://play.google.com/store/apps/details?id=androidx.compose.material.catalog"><img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" height="70"></a><br>**[> Browse on AOSP](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/integration-tests/material-catalog)** <br><br>  | <img src="readme/screenshots/Material_Catalog.png" width="320" alt="Material Catalog sample demo">|


## 高级功能特征（High level features ）

正在寻找具有以下特征的样本？（Looking for a sample that has the following features?

### 自定义布局（Custom Layouts
* [Jetnews: Interests Screen](https://github.com/android/compose-samples/blob/ee198110d8a7575da281de9bd0f84e91970468ca/JetNews/app/src/main/java/com/example/jetnews/ui/interests/InterestsScreen.kt#L428)
* [Jetchat: AnimatedFabContent](https://github.com/android/compose-samples/blob/ee198110d8a7575da281de9bd0f84e91970468ca/Jetchat/app/src/main/java/com/example/compose/jetchat/components/AnimatingFabContent.kt#L101)
* [Jetsnack: Grid](https://github.com/android/compose-samples/blob/73d7f25815e6936e0e815ce975905a6f10744c36/Jetsnack/app/src/main/java/com/example/jetsnack/ui/components/Grid.kt#L27)
* [Jetsnack: CollapsingImageLayout](https://github.com/android/compose-samples/blob/main/Jetsnack/app/src/main/java/com/example/jetsnack/ui/snackdetail/SnackDetail.kt)

### 主题（Theming
* [Jetchat: Material3](https://github.com/android/compose-samples/blob/main/Jetchat/app/src/main/java/com/example/compose/jetchat/theme/Themes.kt#L91)
* [Jetcaster: Custom theme based on cover art](https://github.com/android/compose-samples/blob/main/Jetcaster/app/src/main/java/com/example/jetcaster/util/DynamicTheming.kt)
* [Jetsnack: Custom Design System](https://github.com/android/compose-samples/blob/main/Jetsnack/app/src/main/java/com/example/jetsnack/ui/theme/Theme.kt)

### 动画（Animations
* [Jetsurvey: AnimatedContent](https://github.com/android/compose-samples/pull/842)
* [Jetcaster: Animated theme colors](https://github.com/android/compose-samples/blob/69e9d862b5ffb321064364d7883e859db6daeccd/Jetcaster/app/src/main/java/com/example/jetcaster/util/DynamicTheming.kt)
* [Jetsnack: Animating Bottom Barl](https://github.com/android/compose-samples/blob/main/Jetsnack/app/src/main/java/com/example/jetsnack/ui/home/Home.kt)

### 文本（Text
* [Jetchat: Downloadable Fonts](https://github.com/android/compose-samples/pull/787)

### 大屏（Large Screens
* [Jetcaster - Supporting Pane](https://github.com/android/compose-samples/blob/3dbbf0912b57dacefcfb79191a2d7d6b053dadb8/Jetcaster/app/src/main/java/com/example/jetcaster/ui/home/Home.kt#L282)
* [Jetnews - Window Size Classes](https://github.com/android/compose-samples/blob/69e9d862b5ffb321064364d7883e859db6daeccd/JetNews/app/src/main/java/com/example/jetnews/ui/MainActivity.kt#L36)

### 电视（TV
* [Jetcaster - TV](https://github.com/android/compose-samples/tree/3dbbf0912b57dacefcfb79191a2d7d6b053dadb8/Jetcaster/tv-app)

### 手表（Wear
* [Jetcaster - Wear](https://github.com/android/compose-samples/tree/3dbbf0912b57dacefcfb79191a2d7d6b053dadb8/Jetcaster/wear)

## 格式化（Formatting

To automatically format all samples: Run `./scripts/format.sh`
To check one sample for errors: Navigate to the sample folder and run `./gradlew --init-script buildscripts/init.gradle.kts spotlessCheck`
To format one sample: Navigate to the sample folder and run `./gradlew --init-script buildscripts/init.gradle.kts spotlessApply`

## 更新（Updates

To update dependencies to their new stable versions, run:

```
./scripts/updateDeps.sh
```

To make any other manual updates to dependencies (ie add a new dependency or set an alpha version), update the `/scripts/libs.versions.toml` file with changes, and then run `duplicate_version_config.sh` to propogate the changes to all other samples. You can also update the  `toml-updater-config.gradle` file with changes that need to propogate to each sample. 


## License
```
Copyright 2024 The Android Open Source Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
