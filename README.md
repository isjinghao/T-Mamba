<p align="center">
  <img src="images/T-Mamba-logo.png" width="150">
</p>


# T-Mamba: A Unified Framework with Long-Range Dependency in Dual-Domain for 2D & 3D Tooth Segmentation 🦷✨

This repository is the official implementation of the [T-Mamba: A unified framework with Long-Range Dependency in dual-domain for 2D & 3D Tooth Segmentation](https://arxiv.org/pdf/2404.01065).

## Overview

🔥🔥 The code, pre-trained weights, and datasets are fully available.

Currently, T-Mamba supports both 2D and 3D vision tasks. We welcome you to try it out to improve your model's performance. 

## Dataset 📦

The proposed TED dataset is available at: [Hugging Face](https://huggingface.co/datasets/Bryceee/TED).

## Contact

If you have any questions, please feel free to reach out to me at [isjinghao@gmail.com](mailto:isjinghao@gmail.com).


## Install
```sh
conda create -n tmamba python=3.9
conda activate tmamba
pip install -r requirements.txt

cd Tim/causal-conv1d
python setup.py install
cd ../mamba
python setup.py install

=============================
Requirement specific version:
mamba_ssm==1.0.1
causal_conv1d==1.0.0
=============================
```

## Training
```sh
sh train_3d.sh # for 3D
sh train_2d.sh # for 2D
```

## Testing (for evaluations)
```sh
sh test_3d.sh # for 3D
sh test_2d.sh # for 2D
```

## Inference
```sh
sh infer_3d.sh # for 3D
sh infer_2d.sh # for 2D
```

## Citing T-Mamba

If you use TED3 dataset or the T-Mamba network in your research, please use the following BibTeX entry.

```bibtex
@article{hao2026t,
  title={T-Mamba: a unified framework with long-range dependency in dual-domain for 2D \& 3D tooth segmentation},
  author={Hao, Jing and Zhu, Yonghui and He, Lei and Liu, Moyun and Tsoi, James Kit Hon and Hung, Kuo Feng},
  journal={IEEE Transactions on Multimedia},
  year={2026},
  publisher={IEEE}
}
```
