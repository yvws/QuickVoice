# 集成
## 1. 在root's build.gradle中加入Jitpack仓库
```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

## 2. 在app's build.gradle中添加依赖
```
dependencies {
    ...
    implementation 'com.github.yvws:QuickVoice:1.0.0'
}
```
