![Material design library logo](images/logo.png)

# Material Design Android Library

This is a fork of the original <a href="https://github.com/navasmdc/MaterialDesignLibrary"> Material Design Library Project </a>. I have just renamed one of the resource file to eliminate the the conflict error ""Error:Attribute "color" has already been defined"" which occurs when you use Material Design Library.


You can use the gradle dependency, you have to add these lines in your build.gradle file:

```xml
repositories {
    jcenter();
    maven { url "https://jitpack.io" }
}

dependencies {
    compile 'com.github.vajro:MaterialDesignLibrary:1.3'
}
```
