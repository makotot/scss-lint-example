# Scss-lint example

## BangFormat

`!`の前後に不適切なスペースがある時に警告

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `space_before_bang` | `!`の前にスペースがあるべきか否か | `true` |
| `space_after_bang` | `!`の後ろにスペースがあるべきか否か | `false` |



## BorderZero

`border: none`ではなく`border: 0`を使うようにするか

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `convention` | `0`(zero)と`none`どちらを選択するか | `zero` |



## ColorKeyword

16進カラーコードを使うようにするか



## ColorVariable

色の指定を変数でしか許可しないようにするか



## Comment

`/* ... */`ではなく`//`を使うようにするか



## DebugStatement

`@debug`が残ってないか



## DuplicateProperty

プロパティが重複していないか



## ElsePlacement

`@else`の前後の波括弧で改行しないか

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `style` | 改行するか否か。`new_line`で改行ありにできる | `same_line` |



## EmptyLineBetweenBlocks

ブロックの前に１行あけるかどうか

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `ignore_single_line_blocks` | １行だけのブロックは無視するかどうか | `true` |



## EmptyRule

空のルールセットは許可しない



## FinalNewline

ファイルの最後の行が空行になっているか

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `present` | 最後の行を空行にするか | `true` |



## HexLength

16進カラーコードを短縮して書くことができるとき、短縮するか、しないか

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `style` | 短縮して記述を許容なら`short`、不可なら`long` | `short` |



## HexNotation

16進カラーコードが小文字で記述されているか

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `style` | 小文字(`lowercase`)か大文字(`uppercase`)か | `lowercase` |



## HexValidation

16進カラーコードが３桁か６桁であること



## IdSelector

IDセレクタを使用しない



## ImportantRule

`!important`を使用しない



## ImportPath

`@import`を使用するとき、`_`始まりにしないことと拡張子を含めないこと

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `leading_underscore` | `_`はじまりを許可するか | `false` |
| `filename_extension` | 拡張子を許可するか | `false` |



## Indentation

1インデント2スペースで

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `allow_non_nested_indentation` | | `false` |
| `character` | インデントを`tab`にするか`space`にするか | `space` |
| `width` | インデント字数 | `2` |



## LeadingZero

`0`始まりの小数点の値は、`0`を省略する

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `style` | `0`を含む(`exclude_zero`)・含まない(`include_zero`) | `exclude_zero` |



## MergeableSelector

セレクタを重複して記述していないか

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `force_nesting` | ネスト可能であれば必ずネストさせるか | `true` |



## NameFormat

関数、ミックスイン、変数はハイフンつなぎの小文字で名前をつける

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `arrow_leading_underscore` | `_`はじまりを許容する | `true` |
| `convention` | ハイフンつなぎの小文字かBEMか(`hyphenated_lowercase`か`BEM`) | `hyphenated_lowercase` |



## NestingDepth

深すぎるネストを避ける

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `max_depth` | ネストの深さ | `3` |



## PlaceholderInExtend

`@extend`のセレクタは常にプレースホルダーを利用する



## PropertyCount

ルールセットの中のプロパティの数を制限する

| オプション | 内容       |
|------------|------------|
| `included_nested` | ネストしたルールセットも含めるか否か |
| `max_properties` | プロパティの最大値 |



## PropertySortOrder

厳密にプロパティの順番を決める。デフォルトはアルファベット順。

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `ignore_unspecified` | ソート対象から外す | `false` |
| `order` | ソートしたいプロパティの配列 | `nil` |



## PropertySpelling

存在しないプロパティを使用しているか

| オプション | 内容       |
|------------|------------|
| `extra_properties` | 許容するプロパティ |



## SelectorFormat

セレクタの命名規則

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `convention` | 使用する命名規則 | `hyphenated_lowercase` |
| `ignored_names` | 命名規則のルールの対象外 |  |
| `ignored_types` | 命名規則のルールの対象外とするセレクタのタイプ | |
| `attribute_convention` | 属性セレクタのみに対する命名規則 | |
| `class_convention` | クラスセレクタのみに対する命名規則 | |
| `id_convention` | idセレクタのみに対する命名規則 | |
| `placeholder_convention` | プレースホルダセレクタのみに対する命名規則 | |



## Shorthand

可能な限りショートハンドで



## SingleLinePerProperty

１行につき１つのプロパティで

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `allow_single_line_rule_sets` | １行でルールセットを記述することを許容するか否か | `true` |



## SingleLinePerSelector

１行につき１つのセレクタで



## SpaceAfterComma

カンマの直後に必ずスペースを入れる



## SpaceAfterPropertyColon

プロパティのあとのコロンの直後にいれるスペース

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `style` | スペース１つか、スペースなしか、スペース１つ以上か | `one_space` |



## SpaceAfterPropertyName

プロパティとコロンの間にスペースを入れない



## SpaceBeforeBrace

波括弧の前に１つスペースを入れる

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `allow_single_line_padding` | 1行のルールセットのフォーマットを合わせることを許容するか否か | `false` |
| `style` | スペースか改行か | `space` |



## SpaceBetweenParens

丸括弧の前後にスペースを入れない

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `spaces` | スペースをいくつ許容するか | `0` |



## StringQuotes

文字列をシングルクォーテーションで囲う。エスケープせずにすませるためにダブルクォーテーションを使うのは許容。

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `style` | シングルクォーテーションかダブルクォーテーションか | `single_quotes` |



## TrailingSemicolon

末尾にセミコロンをつける



## TrailingZero

小数点以下に不要な０を入れない



## UnnecessaryManitissa

不要な小数点をつけない



## UnnecessaryParentReference

親要素の参照が不要なときに`&`を使わない



## UrlFormat

urlにプロトコルやドメインを含めない



## UrlQuotes

urlを常にクォーテーションで囲う



## VariableForProperty

特定のプロパティの値を変数でもつこと

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `properties` | チェック対象のプロパティの配列 |  |



## VendorPrefix

ベンダープレフィックスを記述しない。autoprefixerやmixinから付与する。

| オプション | 内容       | 初期値     |
|------------|------------|------------|
| `identifier_list` | | |
| `additional_identifiers` | | |
| `excluded_identifiers` | | |



## ZeroUnit

0に単位をつけない

