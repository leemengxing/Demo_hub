## CV-demo-Hub：

### 概述：

CV常见任务虽然大多都具备客观指标，但人类视觉信息的获取方式决定还是不如视频/图片demo呈现令人惊艳，可视化是CV的一大利器。

本项目记录从业以来做过CV各个方向的demo合集：

#### 1. 图像视觉特效SDK:

##### 人脸关键点：

![](face_landmark\landmark.gif)


关键点抖动解决：direct：表示每一帧都去人脸检测和关键点。post：加入人脸追踪和帧间平滑策略。

##### 美颜和贴纸：

美颜：磨皮、美白、锐化。

![](beauty_sticker\beauty.png)

美型：大眼、瘦脸。

![](beauty_sticker\deform.png)

2d贴纸：



##### 手势识别：

![](gesture/hand.gif)

##### 肢体关键点：

![](pose_landmark/pose.gif)


#### 2. 人像matting：
##### 自动化节日海报：

![](human_matting\test.png)

![](human_matting\compose.png)

##### 任意背景替换：

![](background_replacement/demo.gif)

#### 3. 视线追踪：

专注度指标：

![](gaze_tracking/gaze1.gif)

![](gaze_tracking/gaze2.gif)

### TODO:

- [ ] SDK-MNN部署代码

- [ ] openGL 美颜和贴纸demo

- [ ] 其他技术博客