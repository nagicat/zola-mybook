+++
title = "mybook elements"
date = 2023-10-01
[taxonomies]
categories = ["mybook"]
tags = ["guide"]
[extra]
math = true
+++

# はじめまして
「[mybook](https://github.com/nagicat/mybook)」は、シンプルかつ必要十分な機能を備えたZolaの個人ブログ向けテーマです。**MIT License**の範囲内で利用できます。日本語での利用を想定としたデザインのため、他の言語で利用時には不具合が発生する可能性があります。この文章は表示テストのための文章です。特に意味はなく、この文章に意味はありません。ですから、この文章に意味はないのです。テーマの雰囲気をつかむためにはテーマの雰囲気をつかむ必要があります。

## はじめまして
「[mybook](https://github.com/nagicat/mybook)」は、シンプルかつ必要十分な機能を備えたZolaの個人ブログ向けテーマです。**MIT License**の範囲内で利用できます。日本語での利用を想定としたデザインのため、他の言語で利用時には不具合が発生する可能性があります。この文章は表示テストのための文章です。特に意味はなく、この文章に意味はありません。ですから、この文章に意味はないのです。テーマの雰囲気をつかむためにはテーマの雰囲気をつかむ必要があります。

### はじめまして
「[mybook](https://github.com/nagicat/mybook)」は、シンプルかつ必要十分な機能を備えたZolaの個人ブログ向けテーマです。**MIT License**の範囲内で利用できます。日本語での利用を想定としたデザインのため、他の言語で利用時には不具合が発生する可能性があります。この文章は表示テストのための文章です。特に意味はなく、この文章に意味はありません。ですから、この文章に意味はないのです。テーマの雰囲気をつかむためにはテーマの雰囲気をつかむ必要があります。

#### はじめまして
「[mybook](https://github.com/nagicat/mybook)」は、シンプルかつ必要十分な機能を備えたZolaの個人ブログ向けテーマです。**MIT License**の範囲内で利用できます。日本語での利用を想定としたデザインのため、他の言語で利用時には不具合が発生する可能性があります。この文章は表示テストのための文章です。特に意味はなく、この文章に意味はありません。ですから、この文章に意味はないのです。テーマの雰囲気をつかむためにはテーマの雰囲気をつかむ必要があります。

##### はじめまして
「[mybook](https://github.com/nagicat/mybook)」は、シンプルかつ必要十分な機能を備えたZolaの個人ブログ向けテーマです。**MIT License**の範囲内で利用できます。日本語での利用を想定としたデザインのため、他の言語で利用時には不具合が発生する可能性があります。この文章は表示テストのための文章です。特に意味はなく、この文章に意味はありません。ですから、この文章に意味はないのです。テーマの雰囲気をつかむためにはテーマの雰囲気をつかむ必要があります。

###### はじめまして
「[mybook](https://github.com/nagicat/mybook)」は、シンプルかつ必要十分な機能を備えたZolaの個人ブログ向けテーマです。**MIT License**の範囲内で利用できます。日本語での利用を想定としたデザインのため、他の言語で利用時には不具合が発生する可能性があります。この文章は表示テストのための文章です。特に意味はなく、この文章に意味はありません。ですから、この文章に意味はないのです。テーマの雰囲気をつかむためにはテーマの雰囲気をつかむ必要があります。

# Elements

## コードブロック
```js
if ( true ) {
    console.log("codeBlock");
}
```

## インライン
これは`inlineCode`です。これは**強調**です。これは~~取り消し線~~です。
## 引用
> これは引用ブロックです。

## 画像/動画

## 表

| 見出し | 見出し |
| --- | --- |
| 内容 | 内容 |

一定の幅を超える場合はスクロールされます。

| A | B | C | D | E | F | G | H |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ABCDEFGH | ABCDEFGH | ABCDEFGH | ABCDEFGH | ABCDEFGH | ABCDEFGH | ABCDEFGH | ABCDEFGH |

## リスト
#### 順序付きリスト
1. First item
    1. First item
    1. Second item
    1. Third item
1. Second item
1. Third item

#### 順序なしリスト
- List item
- Another item
- And another item
  - orange
  - apple
    - banana
    - watermelon

## ポイントブロック
文章を目立たせるためのブロックです。

{{ point(type="tip", text="tipブロック") }}
{{ point(type="info", text="infoブロック") }}
{{ point(type="warn", text="warnブロック") }}
{{ point(type="denger", text="dengerブロック") }}

```md
{{/* point(type="tip", text="tipブロック") */}}
{{/* point(type="info", text="infoブロック") */}}
{{/* point(type="warn", text="warnブロック") */}}
{{/* point(type="denger", text="dengerブロック") */}}
```

この下には同じように書かれた要素が存在しますが、typeの指定に誤りがあるため表示されません。
{{ point(type="nagi", text="なにかあります") }}

```md
{{/* point(type="nagi", text="なにかあります") */}}
```

## リンクカード

{{ linkcard(title="タイトルがここに表示されます。タイトルは2行まで表示され、それ以降は省略されます。", link="") }}

```md
{{/* linkcard(title="タイトルがここに表示されます。タイトルは2行まで表示され、それ以降は省略されます。", link="") */}}
```

## {{ inlineimg(src="/emoji/ablobcat_box.webp", alt="blobcat_box") }}インラインイメージ
文章中に、任意の1:1比率の画像{{ inlineimg(src="/emoji/blobcat_smirk.webp", alt="blobcat_smirk") }}を挿入できます。

```md
{{/* inlineimg(src="/emoji/blobcat_smirk.webp", alt="blobcat_smirk") */}}
```