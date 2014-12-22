[![Build Status](https://travis-ci.org/futoase/fizzbuzz.png?branch=master)](https://travis-ci.org/futoase/fizzbuzz)

Mew Calc
====

Overview

## Description

猫の人間の相当年齢を計算する。
2年目は24歳で、その後4歳ずつ増える。
[京都中央動物病院猫のQ&Aの年齢計算式](http://kyotochuoah.com/qa/neko_nenrei.html)を参考。

## Demo

N/A

## VS. 

N/A

## Requirement

Python 2.7.x

## Usage

### インポート方法
```
from mewcalc import MewCalc
```

### 猫の年齢を生まれたdateから計算する
```
from datetime import datetime, date, time
mc = MewCalc()
born = date(1998, 1, 4)
res = mc.calculate(born)
```

### 猫の年齢を年から計算する
```
from datetime import datetime, date, time
mc = MewCalc()
year = 19
res = mc.calculate_by_year(year)
```
### 注意

2年未満の計算は今後作ります。

## Install

```
pip install mewcalc
```

## Contribution

## Licence

MIT.

## Author

[shinriyo](https://github.com/shinriyo/)

