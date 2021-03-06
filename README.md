# StanとRでベイズ統計モデリング サポートページ

## 概要
このリポジトリではデータファイル, Stanコード, 実行するRコード, 図を描くRコード, 画像ファイルを公開しています.

本書では基本的に以下の3つの番号を一致させています.

* モデル式X-Y
* Stanコード（`modelX-Y.stan`）
* 実行するRコード（`run-modelX-Y.R`）

この他に, 図を描くコード`figX-Y.R`があります. また各章のディレクトリの構成は以下になっています.

* `input`:データが格納されています.
* `model`:モデルファイル（Stanコード）が格納されています.
* `output`:作成した図が含まれています.
* `exercise`:練習問題の解答例です.

## 実行方法
各章のディレクトリに移動してから実行することを想定しています. 例えば4章の`run-model4-5.R`を実行する場合にはRを起動後に以下のようにします.

```r
setwd('RStanBook/chap04/')
source('run-model4-5.R')
```

練習問題の解答例を実行するには, さらに`exercise`ディレクトリに移動してから実行することを想定しています.

```r
setwd('RStanBook/chap04/exercise/')
source('ex1.R')
```

## StanやRStanのバージョンアップに伴う補足
[こちら](update.md)

## 正誤表
[こちら](errata.md)

## ソースコードの実行環境
| ソフトやパッケージ名 | 執筆時点 | サポートページ内の現状 |
|:-----------|:------------|:------------|
| OS | Windows 7 SP1 (64bit) | Windows 7 SP1 (64bit) |
| R | 3.3.1 | 3.5.1 |
| Rtools | Rtools34 | Rtools35 |
| Stan | 2.11 | 2.18 |
| rstan | 2.11.1 | 2.18.1 |
| ggplot | 2.1.0 | 3.1.0 |
| ggmcmc | 1.1 | 1.1 |
| GGally | 1.1.0 | 1.4.0 |
| ellipse | 0.3.8 | 0.4.1 |
| hexbin | 1.27.1 | 1.27.2 |
| ggtern | 2.1.1 | 3.0.0 |
| mvtnorm | 1.0.5 | 1.0.8 |
| bda | 5.1.6 | 10.1.9 |
| gtools | 3.5.0 | 3.8.1 |
| Nippon | 0.6.3.1 | 0.7.1 |
| ggrepel | 0.5 | 0.8.0 |
