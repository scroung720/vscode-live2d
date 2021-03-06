# Live2D看板娘 for VSCode

一个简单的Live2D看板娘插件，会跟随你的鼠标动作变化，写代码累了可以逗逗她哦

GitHub: https://github.com/iCharlesZ/vscode-live2d

VSCode Marketplace: https://marketplace.visualstudio.com/items?itemName=CharlesZ.vscode-live2d

model library: https://github.com/iCharlesZ/vscode-live2d-models

## 效果
![效果](./res/demo.gif)

## 安装与卸载

需要 VSCode 1.47.0 以上版本才可以安装此插件！

如果是以System身份安装的VSCode，则需要以管理员身份运行VSCode才可以正常使用看板娘插件。

卸载前需要在设置里将看板娘设置成关闭。或者在 settings.json 中设置 {"vscode-live2d.enabled": false}，然后再卸载插件。如果直接删除插件会有遗留。

## 警告

> **本插件是通过修改 VSCode 的 javascript 文件的方式运行**
> 所以会在初次安装，或者 VSCode 升级的时候，会出现损坏提示，请选择 【不再提示】:

How to remove [unsupported] tag? 怎么去除顶部的[不受支持]的标志？

see here: https://github.com/lehni/vscode-fix-checksums

## 扩展设置

|配置 | 描述
|-----|------------
|`vscode-live2d.enabled`| true:启用插件、false:禁用插件
|`vscode-live2d.model`| 选择看板娘模型
|`vscode-live2d.modelUrl`| 自定义导入模型url
|`vscode-live2d.modelWidth`| 自定义看板娘宽度
|`vscode-live2d.modelHeight`| 自定义看板娘高度
|`vscode-live2d.moveX`| 自定义看板娘水平位置
|`vscode-live2d.moveY`| 自定义看板娘垂直位置
|`vscode-live2d.opacity`| 设置看板娘透明度

## Q&A 常见问题:

---

    Q: It seems that nothing happens after installing the extension? 安装完插件后，似乎没有反应？

    A: Make sure to have the administrator authority！！ 如果不能使用，请确保你有管理员权限！！

---

    Q: How to uninstall? 怎么卸载插件？

    A: Before uninstall, you need to set {"vscode-live2d.enabled": false} in the settings. 卸载前需要在设置里将看板娘设置成关闭。

---

## Release Notes

### 1.3.0 | 2020-07-29

- 移除jQuery相关
- 添加与看板娘的鼠标交互

### 1.2.0 | 2020-07-27

- 增加看板娘宽度高度设置
- 增加看板娘水平垂直位置设置
- 增加看板娘透明度设置

### 1.1.0 | 2020-07-25

- 添加了更多的妹子模型
- 减少了本地模型数量，改成联网获取model，安装插件更快了(切换模型一定要联网)
- 支持以url形式自定义导入live2d模型

### 1.0.0 | 2020-07-25

- 正式版发布

### 0.1.1 | 2020-07-23

- 第一版发布

## 感谢

```
没有这些开源项目，就不会有这个插件的出现
```
* [live2d-widget](https://github.com/stevenjoezhang/live2d-widget)
* [vscode-background](https://github.com/shalldie/vscode-background)

**Enjoy!**
