# Market-HQ 

We enlarge the Market-1501 from 128x64 to 512x256  for 3D Mesh Generation. 
Here we provide a brief script for quick converting. 


## Dependency: 

1. de-jpeg compression (We do not use it in practice, but it works in some general cases.)
https://github.com/victorvde/jpeg2png 


2. super-resolution
https://github.com/xinntao/Real-ESRGAN 

## Download the dataset:

- Market-HQ

Download the processed data from [Google Drive](https://drive.google.com/file/d/10gNi3n8Iny4O4MOZRs5dNFICfj8ri9eW/view?usp=sharing). Or use the [gdrive tool](https://github.com/prasmussen/gdrive/releases/tag/2.1.1) to download via command line:

```
gdrive download 10gNi3n8Iny4O4MOZRs5dNFICfj8ri9eW
```

## Generat data by yourself: 

Please modify the dataset root before running. 
```
python prepare-hq.py 
```

## Citation

Please cite this paper if it helps your research:

```bibtex
@article{zheng20223d,
  title={3D Magic Mirror: Clothing Reconstruction from a Single Image via a Causal Perspective},
  author={Zheng, Zhedong and Zhu, Jiayin and Ji, Wei and Yang, Yi and Chua, Tat-Seng},
  journal={arXiv preprint arXiv:2204.13096},
  year={2022}
}
```
