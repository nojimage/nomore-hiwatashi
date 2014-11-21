/*
Title: レイアウト
Author: nojimage
*/

# 記事はMarkdown形式で記述します
## 見出し2
### 見出し3
#### 見出し4

テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。

見出し1
==========

テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。

見出し2
----------

テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。

## アイキャッチ用見出し {.lead}

テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。

### これも見出しテキストです {.lead}

テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。テキスト。

### リスト
- リンゴ
  - ふじ
  - シナノスイート
- バナナ
- にんじん

### 番号付きリスト
1. リンゴ
  1. ふじ
  2. シナノスイート
2. バナナ
4. にんじん

### 引用

     引用

### 見出しリスト

<ul class="lead">
  <li>リンゴ</li>
  <li>バナナ</li>
  <li>にんじん</li>
</ul>

## インラインフォーマット

Name         | Markup                         | Result           | Tag                           |
-------------|--------------------------------|------------------|-------------------------------|
強調(em)     | `This*is*good`                  | This*is*good     | `This<em>is</em>good`         |
強調(strong) | `This**is**good`                | This**is**good   | `This<strong>is</strong>good` |
コード       | <code>\`This is code\`</code>   | `This is code`   | `<code>This is code</code>`   |
脚注         | `[^1] and [^1]:`                | [^1] で `[^1]:`への脚注が作成されます。 | |

[^1]: `[^1]`の脚注です。

## Block Formatting

### Table

This is a table:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

You can align cell contents with syntax like this:

| Left Aligned  | Center Aligned  | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is      | some wordy text |         $1600 |
| col 2 is      | centered        |           $12 |
| zebra stripes | are neat        |            $1 |

The left- and right-most pipes (`|`) are only aesthetic, and can be omitted. The spaces don’t matter, either. Alignment depends solely on `:` marks.
