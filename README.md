# Income prediction

## Team 14
- Võ Thục Khánh Huyền 20190055
- Trịnh Hồng Phượng 20190062

## Introduction
- It is an competition in Kaggle [link](https://www.kaggle.com/competitions/uet-hackathon-2022-data-science).
- We use this competition to conduct our project for subject: Introduction to Artificial Intelligence.

## How to run
```
conda env create -f conda.yml
conda activate income_pred
```
After that, you can run our notebook in **income_prediction.ipynb**

## Results
| Model         | Validation set | Public test set | Private test set |
|---------------|----------------|-----------------|------------------|
| Random Forest | 0.83217        | 0.83831         | 0.83677          |
| SVM           | 0.47230        | 0.52167         | 0.51461          |
| CatBoost      | 0.92847        | 0.93470         | 0.93283          |

## Material
- [Report](report.pdf)
- [Slide](slide.pdf)