# UE427_CustomCapturePass
UE4在自定义MeshPass中实现CustomSceneCapture渲染  
知乎-翼神  
引擎版本：UE4.27源码版

主要实现在自定义的MessPass中渲染指定场景物体的功能，渲染结果保存在SceneTextures中可在材质中获取。本人是因为一些原因需要单独渲染Niagara粒子到一张RT上，也为了解决原来方案里多个SceneCapture实例运行时产生的性能问题。当然你也可以作为实现某些类似需求的参考。

配套文档：https://zhuanlan.zhihu.com/p/697688164

diff:
https://github.com/sitonmoon/UE427_CustomCapturePass/commit/77ae77c69ffc7123217da71fa1275057e1ab7099  
补充提交：
https://github.com/sitonmoon/UE427_CustomCapturePass/commit/0c52a04b1ad0d3a28e1999f0a78340e981055d09
