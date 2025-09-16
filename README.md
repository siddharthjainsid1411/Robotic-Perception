# Robotic-Perception

# Metric-Semantic SLAM and 3D Gaussian Splatting

This repository contains work on **metric-semantic SLAM** and **3D Gaussian Splatting (3DGS)**.  
The project integrates real-world data capture with advanced mapping and reconstruction techniques, focusing on both localization and semantic understanding.

---

## Part I: Metric-Semantic SLAM

The first part involves metric-semantic reconstruction of a section of the **TCS-X building ground floor**, using an **Intel RealSense Depth Camera**.

### Key Highlights
- Reconstructed a detailed map of the environment  
- Computed **Absolute Trajectory Error (ATE)** for a given trajectory  
- Performed **object-level localization** (example: localizing a specific couch in the environment)  
- Explored improvements in mapping scale and semantic detail  

**Tools Used**: Kimera-SLAM running inside a Docker environment.

---

## Part II: 3D Gaussian Splatting

The second part focuses on **3D scene reconstruction** using Gaussian Splatting from a set of desktop PC images.

### Key Highlights
- Generated high-fidelity **3D reconstruction** of the scene  
- Estimated **camera pose** for novel input views  
- Determined the **relative pose of a power socket** in the reconstructed scene  
- Leveraged GPU acceleration for efficient training and rendering  

---

---

## References

- [Kimera-SLAM](https://github.com/MIT-SPARK/Kimera)  
- [3D Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting)

---

This project demonstrates the integration of **SLAM-based semantic mapping** with **modern 3D neural rendering techniques**, highlighting their potential in robotics and computer vision applications.


