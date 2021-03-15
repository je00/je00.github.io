## 介绍
1. 支持欧拉角、四元数两种模式；
    * 欧拉角模式支持角度、弧度两种单位。
4. 支持鼠标缩放、旋转模型；
    * 支持快速切换正视、侧视等多种视角。
2. 支持更换模型、配色；

## 操作指南

### 绑定数据
* 欧拉角模式，支持绑定X、Y、Z三轴的数据，支持切换弧度和角度单位；

>
X绑定了I0、Y绑定了I1、Z绑定了I3，单位为弧度。

<img src='/img/docs/cube_binding_euler.svg'/>

* 四元数模式，支持绑定X、Y、Z三轴的数据，同时多了一个scalar通道。

>
欧拉角模式下的切换单位按钮，变成了scalar通道。

<img src='/img/docs/cube_binding_quanter.svg'/>


### 缩放和切换视角
通过鼠标滚轮可以缩放模型，拖动可以旋转模型视角。

>
右键菜单<模型视图>子菜单里也支持了多种预设视角。

<img src='/img/docs/cube_view.svg'/>


### 更换模型
* 右键菜单<模型文件>子菜单里，支持更换模型文件，支持obj、stl格式；

<img src='/img/docs/cube_model.svg'/>

* 直接将模型文件拖拽到控件，也可以更换模型。

<img src='/img/docs/cube_model.gif'/>


### 位姿偏置
在控件中央双击，或者在右键菜单勾选<位姿偏置设置窗口>，可以设置模型的位姿偏置。
<img src='/img/docs/cube_offset.svg'/>

### 外观设置
右键菜单<主题>子菜单中，可以设置模型配色等外观。
<img src='/img/docs/cube_theme.svg'/>