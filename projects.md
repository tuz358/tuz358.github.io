---
layout: default
---

## 主な活動
- [SecHack365](https://sechack365.nict.go.jp/)参加 (2018)
- [CODE BLUE2018](https://codeblue.jp/2018/) 学生スタッフ
- 株式会社インテリジェント ウェイブにてインターンシップ (2018)
- セキュリティ・キャンプ全国大会2017参加
- [セキュリティミニキャンプ in 神戸](http://www.security-camp.org/minicamp/kobe2017.html)参加(2017)
- [情報セキュリティスペシャリスト試験](https://www.jitec.ipa.go.jp/1_11seido/sc_28.html)合格(2016年春季)


## 主な制作物(ポートフォリオ)
### 1. 情報セキュリティに関する技術書

「[つくりながら学ぶ! Pythonセキュリティプログラミング](https://book.mynavi.jp/ec/products/detail/id=102144)」、マイナビ出版、ISBN 978-4-8399-6850-2

![book-cover](http://tuz358.github.io/img/book_cover.jpg)

- **概要**: 情報セキュリティ初心者が、自分でPythonコードを実装し動かしながらセキュリティの基礎を学ぶことができる本。ネットワーク、Web、暗号、ファジング、無線技術、仮想化技術等を扱っている。
- 本書で使用されているサンプルコード : [http://gitlab.com/pysec101/pysec101](http://gitlab.com/pysec101/pysec101)

### 2. 自作3軸CNCフライス盤

![CNC](http://tuz358.github.io/img/CNC.jpg)

- **概要**: 各軸(XYZ)がボールねじ+リニアガイドで駆動するCNCフライス盤。プラスチック、木材、アルミを加工可能。
- **使用技術や部品等**: GRBL, CNCjs, Arduino等

### 3. 簡易CPUエミュレータの自作

![cpu-emulator](http://tuz358.github.io/img/cpu-emulator_PoC.png)
[View on GitHub](http://github.com/tuz358/cpu-emulator/)

- **概要**: x86アーキテクチャCPUの基本的な命令セット、レジスタ・メモリ周りの動作を実装。上図は動作例としてフィボナッチ数列を計算する機械語コードを読み込ませた結果(EAXレジスタに返り値として計算結果が格納されている)。
- **使用技術や部品等**: C, C++, NASM

### 4. 自作クアッドコプター

![quadcopter](http://tuz358.github.io/img/quadcopter.png)
[View on GitHub](http://github.com/tuz358/quadcopter_mk-I/)

- **概要**: 小型(全長約90mm)のクアッドコプター。加速度+ジャイロセンサの情報を相補フィルタによりセンサフュージョンして姿勢を推定し、4つのモーター(プロペラ)それぞれの出力を調整することで飛行。
- **使用技術や部品等**: ATMEGA328マイコン, MPU6050, ESP8266, Eagle, Arduino IDE
