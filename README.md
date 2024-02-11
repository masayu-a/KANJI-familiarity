# KANJI-familiarity (version 1.0.0) (2024/02/11)

## Description
常用漢字に対して、クラウドソーシングにより親密度情報・位相情報を付与したもの

## Features 

### KANJI-familiarity.txt

1行目がヘッダ

- 1列目：WID 調査時のID
- 2列目：WORD 表層形
- 3列目：LABEL 漢字のID
- 4列目：FACTOR 印象評定の属性
- 5列目：VALUE 印象評定値

### 漢字印象評定情報.xlsx

#### 元データ

1行目がヘッダ

- 1列目：WID 調査時のID
- 2列目：WORD 表層形
- 3列目：LABEL 漢字のID
- 4列目：FACTOR 印象評定の属性
- 5列目：VALUE 印象評定値

#### 集計結果

1行目がヘッダ

- 1列目：WORD 表層形
- 2列目：LABEL 漢字のID
- 3列目：KNOW 印象評定:「知っている」
- 4列目：ONYOMIWRITE 印象評定:「音読みのものが書くものに現れる」
- 5列目：ONYOMIREAD 印象評定:「音読みのものが読むものに現れる」
- 5列目：KUNYOMIWRITE 印象評定:「訓読みのものが書くものに現れる」
- 7列目：KUNYOMIREAD 印象評定:「訓読みのものが読むものに現れる」
- 8列目：5評定平均: KNOW+LISTEN+READ+SPEAK+WRITE
- 9列目：生産 印象評定: ONYOMIWRITE+KUNYOMIWRITE
- 10列目：受容 印象評定: ONYOMIREAD+KUNYOMIREAD
- 11列目：生産-受容: ONYOMIWRITE+KUNYOMIWRITE-ONYOMIREAD-KUNYOMIREAD

## References

## Credit
- KANJI-familiarity -- 漢字親密度情報 -- version 1.0.0
  浅原正幸   2024/02/11
  
## Contact
masayu-a@ninjal.ac.jp
