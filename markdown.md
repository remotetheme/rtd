
[remotetheme.github.io](https://remotetheme.github.io/) / 
[jekyll-rtd-theme](./)

___

# Markdown

___

## 段落

```
間に空白行があると

段落になります。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
間に空白行があると

段落になります。
</div>
{::options parse_block_html="false" /}

___

## 見出し

```
# 見出し 1

## 見出し 2

### 見出し 3

#### 見出し 4

##### 見出し 5

###### 見出し 6
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
# 見出し 1

## 見出し 2

### 見出し 3

#### 見出し 4

##### 見出し 5

###### 見出し 6
</div>
{::options parse_block_html="false" /}

h1・h2 はこの記述もできます。

```
見出し１
========

見出し２
--------
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
見出し１
========

見出し２
--------
</div>
{::options parse_block_html="false" /}

`{#見出し}` を入れる事で、リンク先の名称を明記する事もできます。

```
### 見出し {#head}
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
### 見出し {#head}
</div>
{::options parse_block_html="false" /}

GitHub Pages では英数だと機能しますが、日本語などは機能しない場合があります。\
GitHub リポジトリ（ソース表示）では機能せずに表示されます。

___

## 太字（bold・強い強調）

HTML 上は「強い強調」ですが、ここでは主な表示である「太字（Bold）」と記載します。

```
ここを **太字** にします。

これでも __太字__ にできます。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
ここを **太字** にします。

これでも __太字__ にできます。
</div>
{::options parse_block_html="false" /}

```
前後に空白がない場合でも**bold**は機能しますが、

こちらの__bold__は機能しない事があります。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
前後に空白がない場合でも**bold**は機能しますが、

こちらの__bold__は機能しない事があります。
</div>
{::options parse_block_html="false" /}

日本語では `**～**` を使うのが無難でしょう。

___

## 斜体（Italic・強調）

HTML 上は「強調」ですが、ここでは主な表示である「斜体（Italic）」と記載します。

```
ここが *Italic* になります。

これでも _Italic_ になります。

日本語フォントでは *機能しない* 場合があります。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
ここが *Italic* になります。

これでも _Italic_ になります。

日本語フォントでは *機能しない* 場合があります。
</div>
{::options parse_block_html="false" /}

日本語では使わないのが無難でしょう。

___

## 太字＋斜体

上 2 種類の強調をあわせた状態です。

```
その1 ***bold + Italic***

その2 **_bold + Italic_**

その3 __*bold + Italic*__

その4 ___bold + Italic___

日本語では ***太字だけ*** の場合があります。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
その1 ***bold + Italic***

その2 **_bold + Italic_**

その3 __*bold + Italic*__

その4 ___bold + Italic___

日本語では ***強調だけ*** の場合があります。
</div>
{::options parse_block_html="false" /}

___

## 引用

```
> 引用の例です。
>
> この中で **太字** なども使えます。
>
> > 引用の中に引用もできます。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
> 引用の例です。
>
> この中で **太字** なども使えます。
>
> > 引用の中に引用もできます。
</div>
{::options parse_block_html="false" /}

___

## 箇条書き（数字）

```
1. １つ目の項目
1. ２つ目の項目
1. ３つ目の項目
```

もちろん `1.` `2.` `3.` … としても構いません。番号は自動付加されます。  
`1.` のみなどの固定した数字ににすると、  
途中に追加する場合でも他の項目を変更する必要がありません。

```
1. １つ目の項目
2. ２つ目の項目
3. ３つ目の項目
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
1. １つ目の項目
1. ２つ目の項目
1. ３つ目の項目
</div>
{::options parse_block_html="false" /}

___

## 箇条書き（固定）

```
- １つ目の項目
- ２つ目の項目
- ３つ目の項目
```

`-` 以外に `+` や `*` も使用できます。

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
- １つ目の項目
- ２つ目の項目
- ３つ目の項目
</div>
{::options parse_block_html="false" /}

___

## 箇条書き（共通事項）


```
- 項目を具体的に説明するために

  このようにして説明する事もできます。

      プログラムなどは頭へ空白 4 文字を
      更に追加して入れます。

- 項目のつづきです。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
- 項目を具体的に説明するために

  このようにして説明する事もできます。

      プログラムなどは頭へ空白 4 文字を
      更に追加して入れます。

- 項目のつづきです。
</div>
{::options parse_block_html="false" /}

___

## コード（code）

```
文中にコードを入れる時は `code` とします。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
文中にコードを入れる時は `code` とします。
</div>
{::options parse_block_html="false" /}

コード内は変換されません。  
`https://test.pages.net.eu.org/` のように自動リンクさせたくない URL の表示にも使えます。

___

## 水平線

```
---
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
---
</div>
{::options parse_block_html="false" /}

3 文字以上が有効です。 `***` や `___` も使用できます。  
また、システムにより `- - -` や `* * *` または `_ _ _` も使用できます。

___

## リンク

```
[test.pages.net.eu.org](https://test.pages.net.eu.org/)
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
[test.pages.net.eu.org](https://test.pages.net.eu.org/)
</div>
{::options parse_block_html="false" /}

リンク先は間接表記も可能です。

```
[test.pages.net.eu.org](https://test.pages.net.eu.org/ "test.pages.net.eu.org")
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
[remotetheme.github.io](https://remotetheme.github.io/ "remotetheme.github.io")
</div>
{::options parse_block_html="false" /}

上のリンク部分にカーソルを当ててみて下さい。

```
<https://remotetheme.github.io/> のように URL へのリンクもできます。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
<https://remotetheme.github.io/> のように URL へのリンクもできます。
</div>
{::options parse_block_html="false" /}

```
システムによって https://remotetheme.github.io/ のように自動リンク化する場合もあります。 
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
システムによって https://remotetheme.github.io/ のように自動リンク化する場合もあります。
</div>
{::options parse_block_html="false" /}

GitHub Pages では機能しないようです。

### GitHub Pages の特記事項

`markdown.md` で作成した場合、そのページへのリンクは  
`markdown` または `markdown.html` となります。  
`markdown.md` は変換されないテキスト表示になります。  
`markdown/` と階層状態は機能しません。

___

## 画像

```
![ふうせん🎈 FU-SEN](https://balloon.asia/apple-touch-icon.png)
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
![ふうせん🎈 FU-SEN](https://balloon.asia/apple-touch-icon.png)
</div>
{::options parse_block_html="false" /}

画像は直接表記も可能です。

```
![ふうせん🎈 FU-SEN](https://balloon.asia/apple-touch-icon.png "ふうせん🎈 FU-SEN")
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
![ふうせん🎈 FU-SEN](https://balloon.asia/apple-touch-icon.png "ふうせん🎈 FU-SEN")
</div>
{::options parse_block_html="false" /}

画像にカーソルを当ててみて下さい。

___

## エスケープ（無効化）

```
変換させたくない場合は \`このように\` \ を付けます。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
変換させたくない場合は \`このように\` \ を付けます。
</div>
{::options parse_block_html="false" /}

英語フォントでは 半角 `＼` ですが、  
日本語フォントではキャラクターコードの定義により、半角 `＼` と 半角 `￥` の場合があります。

___

ここから下の内容はシステムによって採用されていない事があります。

___

## 強制改行

強制改行についてはシステムによって実装が異なります。

```
GitHub や Hugo などは  
これでも改行できます。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
GitHub や Hugo などは  
これでも改行できます。
</div>
{::options parse_block_html="false" /}

上は分かりにくいですが、改行前・行末に半角スペースが 2 つです。

```
GitHub のソースや Hugo などは\
これで改行できます。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
GitHub のソースや Hugo などは\
これで改行できます。
</div>
{::options parse_block_html="false" /}

GitHub Pages は機能しません。

```
HTML タグを入れて<br>
改行できる場合もあります。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
HTML タグを入れて<br>
改行できる場合もあります。
</div>
{::options parse_block_html="false" /}

```
システムによってはこのまま
改行できる場合もあります。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
システムによってはこのまま
改行できる場合もあります。
</div>
{::options parse_block_html="false" /}

これも GitHub Pages では無効です。

___

## 表（table）

```
|見出し|見出し|見出し|
|------|:----:|-----:|
|内容  | 内容 |  内容|
|内容  | 内容 |  内容|
```

見出し と 内容 の間にある `---` は 3 文字以上です。  
`:` の付加により、中央寄せ・右寄せを指定できます。

空白は省略できます。見やすさのために付加できます。

```
|見出し|見出し|見出し|
|------|:----:|-----:|
|内容|内容|内容|
|内容|内容|内容|
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">

|見出し|見出し|見出し|
|------|:----:|-----:|
|内容|内容|内容|
|内容|内容|内容|

</div>
{::options parse_block_html="false" /}

___

## Code ブロック

行単位で ` ```～``` ` を囲んだところが有効です。  
Code プロック内は変換されず、そのまま表示されます。

<div class="language-plaintext highlighter-rouge"><pre class="highlight"><code>```
10 INPUT A
20 INPUT B
30 C=A+B
40 PRINT C
50 END
```</code></pre></div>

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
```
10 INPUT A
20 INPUT B
30 C=A+B
40 PRINT C
50 END
```
</div>
{::options parse_block_html="false" /}

言語や形式を入れる事ができます。  
システムにより Syntax Highlight などで表示が変化します。

<div class="language-plaintext highlighter-rouge"><pre class="highlight"><code>```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```</code></pre></div>

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
</div>
{::options parse_block_html="false" /}

___

## 脚注

```
脚注はこのように使います。 [^1]

[^1]: これが脚注です。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
脚注はこのように使います。 [^1]

[^1]: これが脚注です。
</div>
{::options parse_block_html="false" /}

`1` は任意の文字でも構いません。共通の文字にします。

脚注の説明文は通常ページ下部に表示されます。

___

## 別記載のリンク

リンク URL を文章とは別にまとめて記載する事ができます。  
Markdown の中でもこの説明がされている事は少ないですが、  
オリジナルの Markdown（Markdown.pl）で採用されている機能です。

```
ここから [トップページ][1] へ移動します。

[1]: http://test.pages.net.eu.org/ "test.pages.net.eu.org"
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
ここから [トップページ][1] へ移動します。

[1]: http://test.pages.net.eu.org/ "test.pages.net.eu.org"
</div>
{::options parse_block_html="false" /}

___

## 定義

```
定義
: 説明１
: 説明２
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
定義
: 説明１
: 説明２
</div>
{::options parse_block_html="false" /}

___

## 取り消し線

```
ここに ~~取り消し線~~ が入ります。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
ここに ~~取り消し線~~ が入ります。
</div>
{::options parse_block_html="false" /}

___

## タスクリスト

```
- [x] 完了
- [ ] 未完成
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
- [x] 完了
- [ ] 未完成
</div>
{::options parse_block_html="false" /}

日本ではピンとこないのですが、 ☑ = ☒ なのです。  
Windows 3.1 とか知っている人ならば……

___

## HTML

```
システムによって <strong>HTML</strong> もそのまま使えます。
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
システムによって <strong>HTML</strong> もそのまま使えます。
</div>
{::options parse_block_html="false" /}


GitHub Pages（Jekyll）はデフォルトで HTML タグ内は markdown 変換しません。\
オプション `parse_block_html` を `true` にして、変換を有効にできます。

```
{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
HTML の中で ***Markdown*** も使えます。
</div>
{::options parse_block_html="false" /}
```

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
HTML の中で ***Markdown*** も使えます。
</div>
{::options parse_block_html="false" /}

____

## jekyll-rtd-theme 独自仕様

<div class="language-plaintext highlighter-rouge"><pre class="highlight"><code>```note
note の例。\
複数行で記載もできます。
```</code></pre></div>

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
```note
note の例。\
複数行で記載もできます。
```
</div>
{::options parse_block_html="false" /}

<div class="language-plaintext highlighter-rouge"><pre class="highlight"><code>```tip
tip の例。
```</code></pre></div>

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
```tip
tip の例。
```
</div>
{::options parse_block_html="false" /}

<div class="language-plaintext highlighter-rouge"><pre class="highlight"><code>```warning
warning の例。
```</code></pre></div>

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
```warning
warning の例。
```
</div>
{::options parse_block_html="false" /}

<div class="language-plaintext highlighter-rouge"><pre class="highlight"><code>```danger
danger の例。
```</code></pre></div>

{::options parse_block_html="true" /}
<div style="background: #222; padding: 0 5px;">
```danger
danger の例。
```
</div>
{::options parse_block_html="false" /}

それ以外にも独自仕様が備わっています。

<https://jekyll-rtd-theme.rundocs.io/test/>

___

[remotetheme.github.io](https://remotetheme.github.io/) / 
[jekyll-rtd-theme](./)

___
