## 変更点

オリジナルの[brikis98/wmd](https://github.com/brikis98/wmd)は、Form を作成する Markdown 記法に漢字などの非 ASCII 文字を使用できなかった。これを非 ASCII 文字も Form 記法で使用できるようにした。

## 変更箇所

JavaScript の\w は、ASCII 文字のみにマッチする。そのため漢字やひらがなはこの正規表現にマッチしない。

そこで\w に加えて漢字とひらがな、カタカナにマッチするようにした。
