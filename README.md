# LUPerson
Unsupervised Pre-training for Person Re-identification (LUPerson).

The repository is for the CVPR2021 paper [Unsupervised Pre-training for Person Re-identification](https://arxiv.org/abs/2012.03753).

## LUPerson Dataset
LUPerson is currently the largest unlabeled dataset for Person Re-identification, which is used for Unsupervised Pre-training. LUPerson consists of 4M images of over 200K identities and covers a much diverse range of capturing environments. 

**Details can be found at ./LUP**.

## Pre-trained Models
| Model | path |
| :------: | :------: |
| ResNet50 | [R50](https://drive.google.com/file/d/1pFyAdt9BOZCtzaLiE-W3CsX_kgWABKK6/view?usp=sharing) |

## Finetuned Results
For MGN with ResNet50:

|Dataset | mAP | cmc1 | path |
|:------:|:---:|:----:|:----:|
| MSMT17 | 66.06/79.93 | 85.08/87.63 | [MSMT](https://drive.google.com/file/d/1bV27gwAsX8L3a3yhLoxAJueqrGmQTodV/view?usp=sharing) |
| DukeMTMC | 82.27/91.70 | 90.35/92.82 | [Duke](https://drive.google.com/file/d/1leUezGnwFu8LKG2N8Ifd2Ii9utlJU5g4/view?usp=sharing) |
| Market1501 | 91.12/96.16 | 96.26/97.12 | [Market](https://drive.google.com/file/d/1AlXgY5bI0Lj7HClfNsl3RR8uPi2nq6Zn/view?usp=sharing) |
| CUHK03-L | 74.54/85.84 | 74.64/82.86 | [CUHK03](https://drive.google.com/file/d/1BQ-zeEgZPud77OtliM9md8Z2lTz11HNh/view?usp=sharing)|

These numbers are a little different from those reported in our paper, and most are slightly better.

**The numbers are in the format of `without RR`/`with RR`**.


## Citation

```
@article{fu2020unsupervised,
  title={Unsupervised Pre-training for Person Re-identification},
  author={Fu, Dengpan and Chen, Dongdong and Bao, Jianmin and Yang, Hao and Yuan, Lu and Zhang, Lei and Li, Houqiang and Chen, Dong},
  journal={Proceedings of the IEEE conference on computer vision and pattern recognition},
  year={2021}
}
```
