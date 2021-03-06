# AICP (Android Ice Cold Project) 日本語翻訳ガイドライン (仮)

## 基本ルール

敬体（です、ます）と常体（だ、である）の使い分けや記号は基本的にはJTF日本語標準スタイルガイドに従う。

- [JTF日本語標準スタイルガイド（翻訳用）](https://www.jtf.jp/jp/style_guide/pdf/jtf_style_guide.pdf)（PDFファイル）

小項目 | JTF標準ルール
---|---
本文 | 目的に応じて敬体、常体のどちらかに統一する。
見出し | 常体または体言止め
箇条書き | 「本文」の文体に合わせる。
図表内テキスト | 「本文」の文体に合わせる。
図表のキャプション | 「本文」の文体に合わせる。
句点（。）と読点（、） | 全角の「、」と「。」を使う。
ピリオド（.）とカンマ（,） | 和文の句読点として使用しない。
ひらがな | 全角。昭和61年7月1日内閣告示第1号の「現代仮名遣い」に準じる。
漢字 | 常用漢字表にゆるやかに準じる。
漢字の送りがな | 昭和48年6月18日内閣告示第2号「送り仮名の付け方」に準じる。
複合語の送りがな | 昭和48年6月18日内閣告示第2号「送り仮名の付け方」に準じる。
カタカナ | 全角。半角カタカナは特殊用途を除いて使わない。
カタカナの長音 | 原則として省略しない。
カタカナ複合語 | 中黒または半角スペースで区切る。
算用数字 | 半角
アルファベット | 半角
算用数字（位取りの表記） | 桁区切りには「カンマ」、小数点には「ピリオド」を使う。ただし桁区切りの「カンマ」は省略する場合がある。
ひらがなと漢字の使い分け | 参考文献に従う。
算用数字と漢数字の使い分け | 数えられるものは算用数字。慣用句は漢数字。
一部の助数詞の表記 | 「〜か月」、「〜か所」
全角と半角の間 | スペースなし
全角どうし | スペースなし
半角どうし | 和文中に欧文を引用するなど、和文に欧文が含まれる場合は欧文中の半角スペースを維持する。
カタカナ語間のスペースの有無 | 中黒または半角スペースを入れる。
かっこ類と隣接する文字の間のスペース | スペースなし
句点（。） | 全角
読点（、） | 全角
ピリオド（.）、カンマ（,） | 半角
感嘆符（！） | 全角。和文では多用しない。
疑問符（？） | 全角。和文では多用しない。
スラッシュ（/） | 全角または半角
中黒（・） | 全角
波線（〜または～） | 全角
ハイフン（-） | 原則として和文では使用しない。
コロン（：） | 全角。和文では多用しない。
セミコロン（；） | 原則として和文では使用しない。
ダッシュ（－） | 原則として和文では使用しない。
丸かっこ（） | 全角
大かっこ［］ | 全角
かぎかっこ「」 | 全角
二重かぎかっこ『』 | 全角
二重引用符 "" | 半角。和文では多用しない。
中かっこ {} | 原則として和文では使用しない。
山かっこ ＜＞ | 原則として和文では使用しない。
一重引用符 '' | 原則として和文では使用しない。
単位系 | JIS Z8000-1～Z8000-12「量及び単位」に従う。
単位記号の表記 | 主に、英字による表記とカタカナによる表記がある。英字での表記については、JIS Z8000-1中の「6.5 国際単位系（SI）」に従う。
長さ | mm、km、ミリメートル、センチメートル
質量 | g、kg、t、グラム、キログラム、トン
面積、体積 | ㎡、平方メートル、立法メートル
電気 | A、W、V、アンペア、ワット、ボルト
温度 | ℃
周波数 | Hz、ヘルツ
速度 | m/s、キロメートル毎時、分速～km
伝送速度 | bps、Kbps、バイト/秒
割合 | ％、パーセント
角度 | 90°、90度
記憶容量 | ビット、バイト、Kb、KB、Mb、MB
通貨 | 円、米ドル、ユーロ、＄、USD

### 表中の参考リンク

- 昭和61年7月1日内閣告示第1号「現代仮名遣い」
    - [「現代仮名遣い」に関する内閣告示及び内閣訓令について](http://www.mext.go.jp/b_menu/hakusho/nc/t19860701002/t19860701002.html)
- 昭和48年6月18日内閣告示第2号「送り仮名の付け方」
    - [送り仮名の付け方](http://www.mext.go.jp/b_menu/hakusho/nc/k19730618001/k19730618001.html)
- JIS Z8000-1「量および単位」
    - [JIS Z 8000-1:2014 量及び単位 - 第１部：一般](http://kikakurui.com/z8/Z8000-1-2014-01.html)

## Android 独自のルール

- サマリー（例：設定の「データ使用量」の下に書かれている説明文「60% のデータを使用しています」）は敬体とする。複数の文がある場合は、各文の間にだけ句点を付ける。
- スイッチなどに使われる "ON"、"OFF" は翻訳せず、"ON"、"OFF" のままとする。
- 丸括弧 `(` `)` の内側には、全角文字がきても半角文字がきても間にスペースを入れない。丸括弧 `(` `)` 内には句点は付けない。複数の文がある場合は、各文の間にだけ句点を付ける。丸括弧が末尾にくる場合は、括弧の外に句点を付ける。
- "G+"、"Gerrit" など原文で短縮されている固有名詞は基本的に正式名称（「Google+」、「Gerrit Code Review」など）にする。ただし、表示幅が狭く、正式名称にすると見切れてしまう・レイアウトが崩れてしまう場合は短縮されたままにする。

## 単語前後の半角スペース

- 半角数字の前後には半角スペースを入れない（日時など。例：2009年5月10日12時30分48秒、1個のアプリ、150ピクセル）。
- 半角英字、半角記号の前後には半角スペースを入れる（例：この Android バージョンには対応していません。）。ただし、半角英字、半角記号の前後に句読点がくる場合は半角スペースを入れない。

## スタイルの統一

- 自然な日本語になるよう、原語が受動態の場合も可能な場合は「～されました。」ではなく 「～しました。」などとする。
- "View XX" という表現は基本的に "～を表示" に統一する（～を閲覧、～を見る、～を開く、～を参照、などは使わない）。
- ”Sorry, ..." で始まるエラーメッセージは「すみません」とは訳さず、その部分を削除する。
- 英語で "You" や "Your" とあっても、日本語にしたときに不自然な場合は「あなた」「あなたの」を入れない。「自分の」などを使うか、省略する。
- "下さい" は "ください"、"全て" は "すべて" に統一する。

## プレースホルダー

プレースホルダーは翻訳する文章内で変数を置き換えるためのコードである。例えば、

```
"Disables auto-rotate sensor <xliff:g id="rotate_timeout">%1$s</xliff:g> seconds"
```

という文章を

```
自動回転センサーを<xliff:g id="rotate_timeout">%1$s</xliff:g>秒後に無効にする
```

と翻訳した場合、 `<xliff:g id="rotate_timeout">%1$s</xliff:g>` は数字（秒数）に置き換えられ、「自動回転センサーを2秒後に無効にする」といったように表示される。

プレースホルダーが原文と翻訳で変わったり、プレースホルダーの一部を誤って削除しないよう注意する。

## 翻訳しない文章

- "hh:mm"、"@string/disable_overlays"、"0.3.0"（バージョン番号）など、原文と翻訳が完全に一致するものや翻訳してはいけない文章は翻訳しない。
- "Android"、"AICP Extras"、"Pulse"などの固有名詞は翻訳しない。

## 用語集

用語 | 日本語訳
---|---
About | 一単語で使用されている場合、「このアプリについて」に統一する。ただし、一単語であってもアプリ自体の情報を表示する画面へのリンクテキストおよびタイトルではない場合、「利用統計について」など適宜変更する。
Back (ナビバーのボタン) | 「バック」ではなく「戻る」に統一する。
Home (ナビバーのボタン) | 「ホーム」に統一する。
Recents (ナビバーのボタン) | 「履歴」に統一する。
Device | 「デバイス」「携帯電話」ではなく「端末」に統一する。ただし、「Android デバイス マネージャー」など固有名詞に使われている場合と、「Bluetooth デバイス」「USB デバイス」などスマートフォン・タブレット以外に対して使用される場合は例外とする。
Phone | 「携帯電話」ではなく「端末」に統一する。ただし、通話機能などで区別されて使用される場合は例外とする。
Use ～ | 「～を使う」ではなく「～を使用する」に統一する。
Expanded StatusBar、StatusBar、Notificationsなど | 画面の一番上にある、時計やバッテリーアイコンなどが配置されているバー (ステータスバー) をスワイプして表示される、クイック設定や通知が表示されている画面のことを指している場合、「通知領域」に統一する。
Wipe、Clear | 「ワイプ」「クリア」ではなく「消去」に統一する。

## Contributing

このガイドラインは仮の案であり、Pull Requestを歓迎します。判断に迷う文章や矛盾している箇所があれば、お気軽にどうぞ。

1. Fork it!
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -am 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request :D

## License

```
by Japan Translation Federation (CC BY-SA) www.jtf.jp
本著作物は「JTF日本語標準スタイルガイド2.0」(JTF, CC BY-SA)を改変して作成したものです。
```
