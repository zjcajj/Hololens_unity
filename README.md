# Hololens_unity
使用unity进行场景功能搭建，在HoloLens中部署实现。
# 第一步，unity环境搭建
进入微软官网，按照如下链接中的步骤将MixedRealityFeatureTool插件导入unity中。
[https://docs.microsoft.com/zh-cn/learn/paths/beginner-hololens-2-tutorials/](https://learn.microsoft.com/zh-cn/training/modules/learn-mrtk-tutorials/1-3-exercise-configure-unity-for-windows-mixed-reality?ns-enrollment-type=learningpath&ns-enrollment-id=learn.azure.beginner-hololens-2-tutorials)https://learn.microsoft.com/zh-cn/training/modules/learn-mrtk-tutorials/1-3-exercise-configure-unity-for-windows-mixed-reality?ns-enrollment-type=learningpath&ns-enrollment-id=learn.azure.beginner-hololens-2-tutorials
# 第二步，将代码部署到HoloLens2中
将代码部署到Hololens中有两种方法，一是远程连接。二是使用USB数据线进行连接。这里推荐使用远程连接。因为USB链接容易出现错误，并且现在有部分Hololens2设备不支持USB链接。
在使用远程连接时，首先将代码用visual studio 打开，上方选择ARM64,发布，远程计算机。具体如下图：

![image](https://github.com/zjcajj/Hololens_unity/assets/103746806/d6328262-738e-4cff-b137-e4423899c14b)

然后保持HoloLens设备与计算机处于同一局域网下。在HoloLens设备中查看当前的IP地址。在visual studio项目右键点击属性，再选择调试，将ip地址填入计算机处。点击调试。等待部署成功。具体如下图所示：
![image](https://github.com/zjcajj/Hololens_unity/assets/103746806/a09de15e-5eb1-4b73-bbd4-c7aaeaad3304)
# 第三步，在HoloLens中运行
部署成功后，在HoloLens设备中便可以找到unity图标的软件名。点击打开。即可成功。
