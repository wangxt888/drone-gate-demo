# 无人机系统与飞行 Demo

四旋翼无人机设计与实践项目，涵盖整机搭建、动捕定位、飞控通信、视觉识别与仿真。这里主要展示真机飞行和视觉感知 Demo。

## 真机飞行 Demo

[![室内真机飞行演示](media/flight-preview.gif)](https://wangxt888.github.io/drone-gate-demo/)

**[▶ 在线播放全部视频，无需下载或登录飞书](https://wangxt888.github.io/drone-gate-demo/)**

| Demo | 内容 |
| --- | --- |
| [室内飞行 · 31 秒](https://wangxt888.github.io/drone-gate-demo/#indoor-flight) | 室内起飞、飞行与降落 |
| [近景飞行 · 44 秒](https://wangxt888.github.io/drone-gate-demo/#flight-test) | 真机起飞与悬停测试 |
| [视觉识别 · 58 秒](https://wangxt888.github.io/drone-gate-demo/#vision) | 门洞轮廓、NPU 特征匹配与 AprilTag 三路检测对比 |

## 项目内容

- **系统集成**：四旋翼装配与调试，树莓派与 PX4 飞控通信。
- **定位与感知**：NOKOV 动捕 → VRPN → ROS / MAVROS → PX4；门框视觉检测与相机标定实验。
- **仿真验证**：Blender / Gazebo 场景、PX4 SITL 与视觉穿框任务。

本仓库以 Demo 展示为主；飞行视频与视觉检测视频分别记录阶段实验，不代表已完成真机自主穿框。
