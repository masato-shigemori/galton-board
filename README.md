# Galton Board - 乱数生成アルゴリズムの可視化実験

ガルトンボード（Galton Board）を使った正規分布の可視化と、異なる乱数生成アルゴリズムの比較実験が可能なWebアプリケーションです。

## 背景

このプロジェクトは、Qiita記事「[深層] 乱数は本当にランダムか？」（https://qiita.com/ShigemoriMasato/items/cab847ed75bcd08a99bf）で紹介した乱数生成アルゴリズムを、実際にガルトンボードで実装・可視化したものです。

記事で理論的に解説した疑似乱数の特性や品質の違いを、実際のボールの動きを通して体験できます。

## 実装された乱数生成アルゴリズム

- **Standard Pseudorandom (Math.random)** - JavaScript標準の疑似乱数
- **Linear Congruential Generator (LCG)** - 線形合同法
- **Mersenne Twister** - メルセンヌ・ツイスタ法
- **XORShift Algorithm** - XORShiftアルゴリズム
- **Entropy-based (Mouse Movement)** - マウス操作によるエントロピー収集

## 特徴

- リアルタイムでの物理シミュレーション
- 乱数生成アルゴリズムの切り替え機能
- ボールの速度と生成間隔の調整可能
- 統計情報の表示
- レスポンシブデザイン

## 使用方法

1. ブラウザで https://masato-shigemori.github.io/galton-board/ にアクセス
2. 「Start」ボタンでシミュレーション開始
3. パラメータセクションで乱数生成アルゴリズムを選択
4. ボールの動きと分布の違いを観察

## 技術仕様

- Pure HTML5/CSS3/JavaScript（フレームワーク不使用）
- Canvas APIによる物理シミュレーション
- 複数の乱数生成アルゴリズムの独自実装

## ライセンス

MIT License
