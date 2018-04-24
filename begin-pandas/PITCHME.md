#### _※本スライドは<br>社内向けのよろずLT会用に作成したものです_

---

## 免責
* Pythonもデータ分析も、だいぶ素人です！
* なので、このスライドでは間違ったことや稚拙な箇所もあるかと
* **それでも便利に感じた** ので書きました！
    * ツッコミなど頂けると嬉しいです〜

---

## 話すこと

(私の知っている範囲での)

* Pandasってなーに
* どんなふうにべーんり
* え！そんな事ができちゃうんですか！

---

## 誰向け？

* 「Pandasってなーに」の人
* Pythonてあんまり使ったことないんだけど・・くらいの人
* ちょっとデータ分析？みたいなこと最近したくてさぁ！の人

---

## きっかけ
* 最近、社内でRedashが流行り始めた
* 自分も使ってる
* 外部サービスのAPIを叩いたときに、データの処理(=二次元表に落とす)のが面倒み
* 行と列の結合とか、狙った番地にデータ突っ込んだりがサクッと出来たらいいのになぁ！

---

# Pandasってなーに

---

>Pandasは、プログラミング言語Pythonにおいて、データ解析を支援する機能を提供するライブラリである。特に、数表および時系列データを操作するためのデータ構造と演算を提供する。
([wikipedia](https://ja.wikipedia.org/wiki/Pandas))

---

・・・？

---

## 今回話すこと:
Pandasを使うと、
表の操作がすっごく便利にできる！  

※集計処理etcは扱いません。Pandasの世界観に触れるのが目的

---

## 概念
* DataFrame
    * 行と列のデータ(二次元データ)
* Series
    * 「系列」データ(列データ)

---

## いきなり！Sample

---

例えばこんな表があったとし

| name | color | unit |
| --- | --- | --- |
| apple | red | 1 |
| banana | yellow | 5 |
| strawberry | pink | 10 |

+++

### DataFrameの定義はかんたん！
=「表を作るぞ！」ということ。

### ex:1

[dataframe_1.ipynb](https://github.com/o0h/til/blob/master/notes/dataframe_1.ipynb)

+++

### 列に名前をつけてあげる

[dataframe_2.ipynb](https://github.com/o0h/til/blob/master/notes/dataframe_2.ipynb)

+++

### 行に名前をつけてあげる

[dataframe_3.ipynb](https://github.com/o0h/til/blob/master/notes/dataframe_3.ipynb)

+++

### 辞書を渡してあげるパターン

※辞書 = マップ型。連想配列、ハッシュに相当

[dataframe_4.ipynb](https://github.com/o0h/til/blob/master/notes/dataframe_4.ipynb)

---

## どんなふうにべーんり

---

## TOC

- [x] 表データの作成がとっても簡単
- [ ] 表中のデータへのアクセス(番地)がとっても簡単
- [ ] 表中のデータの絞込がとっても簡単
- [ ] 列や行の追加もとっても簡単
- [ ] 複数の表を結合するのもOK

next: 表中のデータへのアクセス(番地)がとっても簡単

[dataframe_5.ipynb](https://github.com/o0h/til/blob/master/notes/dataframe_5.ipynb)

---

- [x] 表データの作成がとっても簡単
- [x] 表中のデータへのアクセス(番地)がとっても簡単
- [ ] 表中のデータの絞込がとっても簡単
- [ ] 列や行の追加もとっても簡単
- [ ] 複数の表を結合するのもOK

next: 表中のデータの絞込がとっても簡単

[dataframe_6.ipynb](https://github.com/o0h/til/blob/master/notes/dataframe_6.ipynb)

---

- [x] 表データの作成がとっても簡単
- [x] 表中のデータへのアクセス(番地)がとっても簡単
- [x] 表中のデータの絞込がとっても簡単
- [ ] 列や行の追加もとっても簡単
- [ ] 複数の表を結合するのもOK

next: 列や行の追加もとっても簡単

[dataframe_7.ipynb](https://github.com/o0h/til/blob/master/notes/dataframe_7.ipynb)

---

- [x] 表データの作成がとっても簡単
- [x] 表中のデータへのアクセス(番地)がとっても簡単
- [x] 表中のデータの絞込がとっても簡単
- [x] 列や行の追加もとっても簡単
- [ ] 複数の表を結合するのもOK

next: 複数の表を結合するのもOK

- [dataframe_8.ipynb](https://github.com/o0h/til/blob/master/notes/dataframe_8.ipynb)
- [dataframe_9.ipynb](https://github.com/o0h/til/blob/master/notes/dataframe_9.ipynb)
