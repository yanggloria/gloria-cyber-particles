# GLORIA Cyber Particles

一个基于 Three.js + MediaPipe Hands 的赛博风 3D 粒子交互项目。

当前整理版本：`gloria_cyber_particles_center_character_v22_camera_hide_button_v17_perf(1).html`

## 当前版本重点

- 赛博紫色粒子舞台与钻石粒子视觉
- 中央人物粒子模型
- 摄像头手势识别
- 五指分开进入照片滑动模式
- 张开手掌左右移动滑动照片墙
- 五个指尖聚拢选择照片并放大展示
- 展示状态再次聚拢退出
- 摄像头小窗支持拖动、缩放、隐藏/显示
- 针对照片墙和手势识别做了性能优化

## 运行方式

项目是纯前端 HTML 单文件版本，后续把 `index.html` 放到仓库根目录后，可以直接双击打开，也可以用本地服务运行：

```bash
python -m http.server 8000
```

然后浏览器打开：

```text
http://localhost:8000
```

## 权限说明

开启手势识别时，浏览器会请求摄像头权限。建议使用 Chrome、Edge 或手机 Chrome/Safari 测试。

## 后续建议

- 保留稳定版为 `index.html`
- 历史版本放到 `versions/` 目录
- 每次大改前先复制一个新版本，避免覆盖稳定版本
- 如果启用 GitHub Pages，建议将根目录 `index.html` 作为展示入口
