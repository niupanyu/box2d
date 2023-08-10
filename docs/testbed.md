# Testbed
Once you have conquered the HelloWorld example, you should start looking
at Box2D's testbed. The testbed is a testing framework and demo
environment. Here are some of the features:
- Camera with pan and zoom.(可移动和缩放的摄像机)
- Mouse picking of shapes attached to dynamic bodies.
- Extensible set of tests.
- GUI for selecting tests, parameter tuning, and debug drawing options.
- Pause and single step simulation.
- Text rendering.

![Box2D Testbed](images/testbed.png)

The testbed has many examples of Box2D usage in the test cases and the
framework itself. I encourage you to explore and tinker with the testbed
as you learn Box2D.

Note: the testbed is written using [GLFW](https://www.glfw.org) and
[imgui](https://github.com/ocornut/imgui). The testbed is not part of the
Box2D library. The Box2D library is agnostic about rendering. As shown by
the HelloWorld example, you don't need a renderer to use Box2D.
(GLFW的主要功能是创建和管理窗口，OpenGL上下文，同时还能处理手柄，键盘和鼠标输入功能;imgui是一个ui库，imgui值负责计算顶点数据，准备纹理，shader，然后具体的渲染交给后端GLFW，基本的控件label，text, checkbox, slider, 窗体控件：树形控件，图片控件，列表，菜单栏)