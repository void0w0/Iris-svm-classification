# Iris-svm-classification
irisデータセットを用いたSVMによる多クラス分類。 標準化・統計分析・学習曲線・混同行列・決定境界の可視化まで一連の機械学習パイプラインを実装

Multi-class classification using SVM on the Iris dataset. Implements a full machine learning pipeline including statistical analysis, learning curves, confusion matrix, and decision boundary visualization.

## Tech Stack 使用技術

- Python / Jupyter Notebook
- scikit-learn
- pandas / numpy / matplotlib
- mlxtend

## Models Used 使用モデル

- SVM（SVC） : 4特徴量
- SVM（SVC） : 2特徴量（PetalLength・PetalWidth）

## Evaluation Criteria 評価観点

- Accuracy 正解率
- Learning curves 学習曲線
- Confusion matrix 混同行列
- Classification report（Precision・Recall・F1-score）
- Decision boundary visualization 決定境界の可視化

## Dataset データセット

- Iris dataset（scikit-learn built-in）
- 150件 / 3クラス（setosa・versicolor・virginica）/ 4特徴量

## Setup セットアップ

1. Install dependencies / 必要なライブラリをインストール

pip install scikit-learn pandas numpy matplotlib mlxtend japanize-matplotlib

2. Launch Jupyter Notebook
jupyter notebook
