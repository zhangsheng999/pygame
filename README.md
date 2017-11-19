# pygame

## 要求   
#### 用pygame写一个游戏

## pygame背景介绍

#### Pygame是跨平台Python模块，专为电子游戏设计，包含图像、声音。建立在SDL基础上，允许实时电子游戏研发而无需被低级语言（如机器语言和汇编语言）束缚。包含图像、声音。

#### 建立在SDL基础上，允许实时电子游戏研发而无需被低级语言（如机器语言和汇编语言）束缚。基于这样一个设想，所有需要的游戏功能和理念都（主要是图像方面）都完全简化为游戏逻辑本身，所有的资源结构都可以由高级语言提供，如Python。

### Pygame 原为代替突然停止的 pySDL

### Pygame 作者是 Pete Shinners 协议为 GNU Lesser General Public License

## 安装过程对我来说是一个极其耗时的事情，知道交作业的最后一周才知道怎么安装。。。（天资愚钝，即使按照网上的安装教程，也没弄好。后来看了别的同学的作业上的安装过程，按照他的方法试了一下，终于是成功了。。。）

### 1,绘制一个矩形。为了增添一些乐趣，咱们这次绘制一个可以移动的矩形，而不只是单单的在屏幕中间绘制。  首先，需要设置pos_x, pos_y 两个变量来记录矩形的位置信息，然后在创建一对速度变量（vel_x,vel_y），在while循环内不断的更新矩形的位置。当矩形到达屏幕边缘的时候，将速度变量取反，这样就可以产生碰撞的效果了。
[代码](https://github.com/zhangsheng999/1111/blob/master/%E6%96%B0%E5%BB%BA%E6%96%87%E6%9C%AC%E6%96%87%E6%A1%A3%20(2).txt)

游戏截图
![](http://images2015.cnblogs.com/blog/798142/201511/798142-20151115170154759-1135845346.png)


### 2,画大饼游戏     当玩家按下1、2、3、4相应的按键时，就会在程序中绘制相应的饼块，当整个饼块都被绘制完成的时候，颜色会变为亮绿色。

[代码](https://github.com/zhangsheng999/1111/blob/master/%E6%96%B0%E5%BB%BA%E6%96%87%E6%9C%AC%E6%96%87%E6%A1%A3%20(3).txt)

游戏动图
![](https://github.com/zhangsheng999/1111/blob/master/The%20Pie%20Game%20-%20Press%201%2C2%2C3%2C4%202017_11_19%2019_42_01%20(2).mp4)


### 3,打飞机游戏  
[文件](https://github.com/Kill-Console/PythonShootGame/tree/master/resources)

[代码](https://github.com/zhangsheng999/1111/blob/master/%E6%96%B0%E5%BB%BA%E6%96%87%E6%9C%AC%E6%96%87%E6%A1%A3.txt)

游戏截图
![](http://images.cnitblog.com/blog/459135/201309/26093310-1f163fee95714bafab1d773e13df384d.png)


### 致谢  
#### 感谢同学教我安装pygame
#### 参考网站

[用Python和Pygame写游戏-从入门到精通](https://eyehere.net/2011/python-pygame-novice-professional-1/)

[【python游戏编程之旅】](http://www.cnblogs.com/msxh/p/4966899.html)

[【使用pygame制作打飞机游戏】](http://www.cnblogs.com/dukeleo/p/3339780.html)
