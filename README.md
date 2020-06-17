## 注意事项：
1、生成的exe文件较大，点击exe文件之后需要等待几秒才会出现运行界面，期间*请勿关闭exe窗口*  
2、由于软件工具包暂时不支持中文路径，因此存放切片的文件夹请使用**英文**命名，否则加载不出来  
3、某些操作比较耗时，鼠标会变成*圆圈加载*状态，耐心等候即可，详见使用说明  

## 使用说明
### 1、运行程序并选择包含tiff格式的文件夹
点击exe文件之后会出现黑框，几秒后即出现运行界面
![](https://github.com/lpw007/ManualStitcher/raw/master/imgs/initial.jpg)  
打开文件菜单，点击打开按钮选择对应的文件夹
![](https://github.com/lpw007/ManualStitcher/raw/master/imgs/openFile.jpg)   
点击打开按钮之后需要对切片进行一些处理操作，需要花费一点时间，此时鼠标处于**环形旋转**状态，耐心等待即可**
加载完成之后的界面如下:  
![](https://github.com/lpw007/ManualStitcher/raw/master/imgs/loadFile.jpg)   
### 2、手工拼接操作
**a**.使用快捷键*Ctrl+鼠标滚轮*或者顶部菜单栏的*缩放按钮*对切片进行缩放，缩放后的效果如下：  
![](https://github.com/lpw007/ManualStitcher/raw/master/imgs/zoomIn.jpg)   
**b**.缩放完成之后点击菜单栏上方布局设置，选择切片对应的排列方式，此例中为纵向排列，点击之后得到各切片的位置关系如下：  
![](https://github.com/lpw007/ManualStitcher/raw/master/imgs/layout.jpg)  
**c**.得切片的排列方式之后，使用鼠标可实现对各个切片的**旋转**和**平移**操作，同时还支持对切片进行水平(**快捷键H**)和上下翻转(**快捷键V**):  
![](https://github.com/lpw007/ManualStitcher/raw/master/imgs/flip.jpg)  
**d**.在执行拼接操作时，可打开对应的大体图片进行比对，如下所示：  
![](https://github.com/lpw007/ManualStitcher/raw/master/imgs/duibi.jpg)  
**e**.经过鼠标操作之后，得到最终的拼接图如下:  
![](https://github.com/lpw007/ManualStitcher/raw/master/imgs/stitched.jpg)  

### 3、标注与测量操作
**a**.在上一步得到拼接图之后，点击菜单栏的**手动拼接完成按钮**或**快捷键C**保存拼接结果，由于生成图的尺寸较大，因此需要等待几秒.  
**b**.在上一步之后，点击**开始标注**按钮进入标注界面，使用**右键**可选择进行各类操作：  
![](https://github.com/lpw007/ManualStitcher/raw/master/imgs/label.jpg)  
**c**.各种标注操作的补充：  
1、**标注直径**：当右键选择标注直径时，鼠标左键点击两次自动完成直径的生成，同时径长显示在直径中间区域  
2、**删除直径**：从右键中选择删除线时，会删除最近添加的直径  
3、**标注区域**：当选择标注区域时，在已经设置多个点的情况下支持三种方式完成绘制：*使用快捷键**Enter***、*双击两次鼠标左键*、*鼠标回到第一点处会出现白色圆圈，左键点击即可*。  
4、**编辑区域**：在完成上一次区域标注之后可以右键点击*编辑区域*使鼠标回到正常形式(进入编辑状态)，在编辑状态下可通过鼠标移动控制点*改变区域形状*或者在*边上添加新的控制点*，此外可以*删除指定区域*。  
**d**.缩放操作:   
以鼠标所在点为中心进行缩放，缩放操作和拼接部分一致(**Ctrl+滚轮**或者**菜单栏的缩放按钮**)，支持较大倍数的缩放操作。



