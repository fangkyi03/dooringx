<!--
 * @Author: yehuozhili
 * @Date: 2021-01-31 20:44:16
 * @LastEditors: yehuozhili
 * @LastEditTime: 2021-07-12 21:00:48
 * @FilePath: \dooringx\packages\dooringx-lib\README.md
-->

## Dooringx-lib 
## changelog

- 0.3.0 
1、增加标尺，ContainerWrapper需要传递config才可使用。
2、修改容器最小拖动667。修复画布缩放下拖拽时与鼠标距离不一致。
3、innerContainerDragUp需要传递config。

- 0.2.0 commander的传递进行修改，可以获得config了，commander不再从index中导出 ，需要使用时从config中获取。增加左侧类名，方便自定义。
- 0.1.10 修改eslint依赖推荐
- 0.1.9 增加全局body设置
- 0.1.8 增加弹窗设置，移除modalContainer
- 0.1.7 修改预览特殊条件显示，删除console
- 0.1.6 调整初始缩放，画布初始比例，增加回正画布功能。
- 0.1.5 删除未作按钮，增加fixed配置
- 0.1.4 基础功能


## todo

1、制作标尺
2、重构拖拽，优化性能与config传递。