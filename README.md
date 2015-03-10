Markdown記法サンプル用

# 見出し1

## 見出し2

### 見出し3

#### 見出し4

##### 見出し5

###### 見出し6

---

ここは段落（\<p>）です。♪むかしむかし浦島が、助けた亀に連れられて。って浦島呼び捨てかよ！ さん付けしてやれよ！

タグとして認識されたくない、表示したい文字の直前にエスケープ文字を記述します。

```
\<p></p>
```

- **強調 strongです。** __これも強調です。__ <strong>strongタグです。</strong>
- *斜体 italicです。* _これも斜体です。_ <i>iタグです。</i>
- ***強調斜体です。*** ___強調斜体です。___ <em>emタグです。</em>
- ~~対応に差があるみたいだけど取り消し線。~~ <s>sタグです。</s>

> 引用します

> > 引用のネストです

> 上に一行空けないとネストのままです

---

水平線（\<hr>）各種

* * *
***
*****
- - -
---------------------------------------
---

- 箇条書きリスト
* 箇条書きリスト
- 二階層め・箇条書きリスト
+ 箇条書きリスト

---

1. 番号付きリスト
1. 番号付きリスト
1. 二階層め・番号付きリスト
1. 三階層め・番号付きリスト
1. 三階層め・番号付きリスト
1. 二階層め・番号付きリスト
1. 番号付きリスト

---

```
バッククォート3個ずつでくくるとソースコード <pre><code> です。
###ここにはMarkdown書式は効きません
/* コメント */
testtest // コメント
```

```HTML
<!DOCTYPE html>
<head>
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<title></title>
```

```css
body { display: none; }
```

```php
<?php if (is_tag()){ $posts = query_posts($query_string . '&showposts=20'); } ?>
```

バッククォート1個ずつで囲むとインラインのコード \<code></code> です。`body { visibility: hidden; }`

---

テキストリンク [WIRED.jp](http://wired.jp/ "WIRED.jp")

画像埋め込み
![うきっ！](http://mkb.salchu.net/image/salchu_image02.jpg "salchu_image02.jpg")

---

| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This | This | This |
| column | column | column |
| will | will | will |
| be | be | be |
| left | right | center |
| aligned | aligned | aligned |

（Kobitoのヘルプmdから拝借しました）

---

from [Markdown記法 表示確認用サンプル - Qiita](http://qiita.com/salchu/items/da81122ed50b35feda4d "Markdown記法 表示確認用サンプル - Qiita")
