# season-data-NPB

日本野球機構(NPB)から取得したシーズンごとの対戦結果のデータセット．

## Demo

データセットの一部

> `head 2022.csv`

```
date,home,away,hscore,ascore
2022/03/25,読　売,中　日,4,2
2022/03/25,横浜DeNA,広島東洋,3,11
2022/03/25,阪　神,東京ヤクルト,8,10
2022/03/25,東北楽天,千葉ロッテ,0,4
2022/03/25,埼玉西武,オリックス,0,6
2022/03/25,福岡ソフトバンク,北海道日本ハム,4,1
2022/03/26,読　売,中　日,7,5
2022/03/26,横浜DeNA,広島東洋,5,10
2022/03/26,阪　神,東京ヤクルト,0,6
```

## Features

シーズンごとにデータセットを用意しました．

データのヘッダー情報は

- `date`: 試合の日付
- `home`: ホームチーム名
- `away`:アウェイチーム名
- `hscore`:ホームチームのスコア
- `ascore`:アウェイチームのスコア

## URLs

- 日本野球機構：<https://npb.jp/>
- Wikipedia:日本野球機構：<https://ja.wikipedia.org/wiki/%E6%97%A5%E6%9C%AC%E9%87%8E%E7%90%83%E6%A9%9F%E6%A7%8B>

## Author

- 作成者：高橋克征（Takahashi Katsuyuki）
- E-mail：Takahashi.Katsuyuki.github@gmail.com

## Note

- 試合中止になった場合，得点情報は記述されていません．
- 文字コードは`UTF-8(BOM)`としています．

## License

"season-data-NPB" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
