# TtitleTextCell

Android仿iOS单元格（主标题+副标题）

![](http://upload-images.jianshu.io/upload_images/2746415-9c36bd5b1708c651.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## Installing

Users of your library will need add the jitpack.io repository:

```gradle
allprojects {
 repositories {
    jcenter()
    maven { url "https://jitpack.io" }
 }
}
```

and:

```gradle
dependencies {
    compile 'com.github.zhouchupen:TtitleTextCell:v1.0'
}
```

Note: do not add the jitpack.io repository under `buildscript` 

## Adding a sample app 

If you add a sample app to the same repo then your app needs to depend on the library. To do this in your app/build.gradle add a dependency in the form:

```gradle
dependencies {
    compile project(':library')
}
```

where 'library' is the name of your library module.

## Using

You may need this to use the cell.  Put this into your xml file:
```xml
<com.scnu.zhou.widget.TitleTextCell
     android:layout_width="match_parent"
     android:layout_height="wrap_content"
     app:title="姓名"
     app:text="周楚鹏"
     app:isdivider="true">

</com.scnu.zhou.widget.TitleTextCell>
```
