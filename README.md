# TRBAIAC-PAVE
This is the benchmark model for TRB AI Committees Open Data Challenge on pavement distress detection and analysis. Top-down views of pavement image data containing 7 main distress types annotated with bounding boxes are provided (via aiac_main.ipynb). The repo also includes a tutorial on how to train, test models and submit results for evaluation. The modeling framework uses a deep convolutional neural network model with an architecture borrowed from YOLOV5.

<div align="center">
    <a>
        <img src="https://github.com/UM-Titan/TRBAIAC-PAVE/blob/main/aiac.png" width="100%"/>
    </a>
    
</div> 

## <summary> HOW TO RUN </summary>

```bash
$ git clone 'https://github.com/UM-Titan/TRBAIAC-PAVE.git'
$ cd 'TRBAIAC-PAVE'
$ open and run aiac_main.ipynb # google collaboratory is preffered
```

## <summary> RULES </summary>
We expect you to respect the spirit of the competition and do not cheat.
* There is no restriction on the size of the team.
* The use of external data is forbidden.
* Manually annotating test datasets is forbidden.
* Pre-trained models are allowed in the competition.
* We encourage teams to share their source codes and trained models. Python Notebooks are desirable for sharing codes.

## Reference
## [The 1st Data Science for Pavements Challenge (arXiv 2022)](https://arxiv.org/abs/2206.04874)
Corresponding paper to cite:
```
@article{Ashkan2022,
  author    = {Ashkan Behzadian, Tanner Wambui Muturi, Tianjie Zhang, Hongmin Kim, Amanda Mullins, Yang Lu, Neema Jasika Owor, Yaw Adu-Gyamfi, William Buttlar, Majidifard Hamed, Armstrong Aboah, David Mensching, Spragg Robert, Matthew Corrigan, Jack Youtchef, Dave Eshan},
  title     = {The 1st Data Science for Pavements Challenge},
  journal   = {arXiv e-prints},
  volume    = {abs/2206.04874},
  year      = {2022},
  url       = {https://arxiv.org/pdf/2206.04874},
  eid       = {	arXiv:2206.04874},
  eprint    = {2206.04874}
}
```
