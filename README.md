# 相関係数の学習プロジェクト

このプロジェクトは、統計学における相関係数の概念を理解するための教育用リソースです。

## 概要

3種類の相関係数について、数式、特徴、使用場面を散布図とともに解説します：

- **ピアソンの相関係数 (Pearson's Correlation Coefficient)**: 線形関係を測定
- **スピアマンの順位相関係数 (Spearman's Rank Correlation Coefficient)**: 単調関係を測定
- **チャタジーの順位相関係数 (Chatterjee's Correlation Coefficient)**: 任意の関数関係を測定

## 内容

- 各相関係数の数式と計算方法
- 異なるデータパターンでの相関係数の挙動比較
- 視覚的な説明（散布図、順位変換の可視化）
- 実装例（Python）

## ファイル構成

```
notebooks/
  └── correlation.ipynb    # メインのJupyterノートブック
```

## 使用技術

- Python 3
- NumPy: 数値計算
- Matplotlib: データ可視化
- SciPy: 統計関数

## 実行方法

Jupyterノートブックを開いて、セルを順番に実行してください：

```bash
jupyter notebook notebooks/correlation.ipynb
```

## 学習ポイント

1. **ピアソン相関**: 線形関係の検出に最適
2. **スピアマン相関**: 非線形だが単調な関係も検出可能、外れ値に頑健
3. **チャタジー相関**: U字型などの非単調な関数関係も検出可能、非対称性がある

## 参考文献

- Chatterjee, S. (2021). "A new coefficient of correlation." Journal of the American Statistical Association, 116(536), 2009-2022.
- [解説記事](https://qiita.com/Islay_tr/items/dd427ba86ba11bd25626)
