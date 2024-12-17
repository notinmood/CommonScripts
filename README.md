# 说明
常用脚本、工具收集。

本项目托管于 https://github.com/notinmood/CommonScripts ，但因为国内的网络情况，就在 https://gitee.com/xiedali/CommonScripts 做了同步。同步方法也非常简单：在gitee项目名称的后面点击带有双箭头的小圆形图标，即可。

## linux 工具
### /linux/docker_pull.sh 
1. 使用最快的docker源拉取image镜像。使用方法 `bash -c "$(curl -sSLf https://gitee.com/xiedali/CommonScripts/raw/main/linux/docker_pull.sh)" -s hello-world:latest`，其中将 “hello-world:latest”换成你希求的镜像名称和版本
2. 在使用中如果本脚本内置的所有源都失效了，可以用文本编辑工具打开本脚本，替换local mirrors=（）圆括号内的内容。



## 第三方工具

### centos换源
脚本 `bash <(curl -sSL https://gitee.com/SuperManito/LinuxMirrors/raw/main/ChangeMirrors.sh)`
