# WinGup开源升级器

## 环境
- 使用VS2017
- win10



## 配置

```
// 强制更新且静默模式
GUP.exe -forceUpdate -slientMode 
```





## 修改记录
> 主要修改的地方都在winmain.cpp
- 默认为依据className来kill程序，修改为根据应用程序名来kill
- 去除配置文件的SlientMode
- 新增强制更新选项-forceUpdate，强制更新时无法取消并自动重启
- 隐藏没必要的提示框，如取消成功

## 打包方式
- ![](README_files/1.jpg)
- ![](README_files/2.jpg)
- 然后在项目下的bin即是编译后的文件

## 参考
[git](https://github.com/yousiqi/wingup)
