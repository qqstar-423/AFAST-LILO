# AFAST-LILO

**AFAST-LILO: An Adaptive Tightly Integrated LiDAR-IMU-Leg Odometry System for SLAM in Underground Cable Tunnels**

## Status

🚧 This repository is currently under construction.
The full source code, configuration files, and documentation associated with this work will be **released after the paper is accepted for publication**.

## Overview

The proposed AFAST-LILO method is specifically developed to address the challenges encountered in underground cable tunnel, which are characterized by long, homogeneous structures. The system pipeline is depicted in Fig. \ref{fig1}. The proposed method integrates information from LiDAR, IMU, and leg odometry to achieve robust and accurate localization. In the preprocessing module, LiDAR points corresponding to cable racks are identified to enhance feature extraction. The adaptive weight module dynamically adjusts the measurement noise covariances of both the leg odometry and LiDAR data to improve system resilience. Subsequently, the state estimation module employs the IESKF to obtain optimal state estimates for the robot, ensuring accurate localization and mapping in challenging environments.
<img width="1273" height="695" alt="image" src="https://github.com/user-attachments/assets/d8ad7b97-161b-475e-9c61-6957da21013e" />

## Planned Release

After acceptance, this repository will include:

* Source code
* Configuration files
* Launch / run instructions
* Dataset preprocessing scripts
* Example bag files or benchmark instructions

## Paper

A preprint / citation information will be added here after publication.

## Contact

For questions regarding this work, please contact:

* **Name:** Yujian Qiu
* **Email:** [qiuyujiancqupt@163.com](mailto:qiuyujiancqupt@163.com)

## Citation

```bibtex
@article{Zhu2026afastlilo
  title={An Adaptive Tightly Integrated LiDAR-IMU-Leg Odometry System for SLAM in Underground Cable Tunnels},
  author={Hao Zhu, Yujian Qiu, Yuqiu Mu, Sin-Chi Kuok, Henry Leung},
  journal={Under review},
  year={2026}
}
```
