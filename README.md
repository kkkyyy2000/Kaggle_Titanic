# Kaggle Titanic
[Kaggle-Titanic-](https://www.kaggle.com/competitions/titanic/overview)コンペティションに参加しました。
このコンペでは、タイタニック号の乗客のうち誰が生き延びたかを予測する必要があります。
最終的に、xgboostを用いて参加者の上位2%の成績を達成することができました。

## Overview
### titanicディレクトリ
- gender_submission.csv : 提出フォーマットの例
- train.csv : 学習データ
- test.csv : テストデータ


### Kaggle-Titanic-の流れ
- セットアップ
- 学習データ、テストデータの結合
- データの概要と欠損値の確認
- 各説明変数のグループ分け、欠損値補完、ラベルエンコーディング
- Family_size説明変数を作成
- 説明変数を作成（家族データ深掘り）
- 前処理2（説明変数選別、ダミー変数化、標準化、データ分割）
- モデルを構築（決定木, xgboost）、学習、評価
- 提出フォーマットに整形

## Description
Kaggle-Titanic-の詳細については以下の記事を確認する事
- [Qiita](https://qiita.com/yk777/items/3a455b39d0a371a05519)

## Requirements
- Jupyter Notebook
- Python==3.8
- numpy==1.19.2
- pandas==1.1.3
- sklearn==0.23.2
- matplotlib==3.3.2
