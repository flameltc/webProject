# Piexel Painter

## 功能

* 使用canvas绘制，节省内存提升性能
* 使用websocket进行实时传输
* 使用express构建http服务器
* 使用ws模块构建websocket后端并与express集成
* 后端使用buffer保存图片数据
* 后端自动保存图片状态，服务器重启不影响数据
* 首次打开页面，后端将图片转为png编码传给前端，以节省浏览，加快打开速度
* 取色功能，以及取色实时提示
* 缩放
* 移动