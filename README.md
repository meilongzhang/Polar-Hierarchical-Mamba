# Polar Hierarchical Mamba: Towards Streaming LiDAR Object Detection with Point Clouds as Egocentric Sequences

<!-- [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/abs/2406.10700) -->

This repo is the official implementation of our WACV 2026 paper Towards Streaming LiDAR Object Detection with Point Clouds as Egocentric Sequences. Our Polar Hierarchical Mamba model achieves start-of-the-art streaming performance on Waymo Open. It processes partial sectors of scanning LiDAR outputs via a polar-native 3D backbone and streaming sector buffer, achieving full-scan accuracy at streaming speed.

## 🔥News
-[25-11-11] Towards Streaming LiDAR Object Detection with Point Clouds as Egocentric Sequences is accepted by **WACV 2026!**
-[25-04-28] Polar Hierarchical Mamba is accepted by **4DV @ CVPR 2025!**

## 📘TODO
- [ ] Release the arXiv version.
- [ ] Clean up and release the code.
- [ ] Release code of Waymo.
- [ ] Release code of NuScenes.
- [ ] Release code of visualization and evaluation metrics.
- [ ] Merge Polar Hierarchical Mamba to [OpenPCDet](https://github.com/open-mmlab/OpenPCDet).

## Acknowledgments
PHiM is based on [OpenPCDet](https://github.com/open-mmlab/OpenPCDet) and [Voxel Mamba]([https://github.com/gwenzhang/Voxel-Mamba]).  
We also thank the CenterPoint, TransFusion, OctFormer, Mamba, and HEDNet authors for their efforts.
