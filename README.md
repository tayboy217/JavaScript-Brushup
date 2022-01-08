# JavaScript-Brushup
## JavaScriptの復習
1. JavaScriptの歴史<br>
- 1995年 NetscapeNavigator 2.0に搭載(旧名 : LiveScript)
- 1996年 IE 3.0にJavaScriptに似た言語JScriptを搭載 ※互換性に悩む
- 1997年 ES1 初版
- 1998年 ES2
- 1999年 ES3 IE6でも動く。最も知られている。JQueryが普及。
- 2009年 ES5 現行のブラウザでは、ほぼ確実に動作する。ES3からは小規模な変更。
- 2015年 ES2015 (ES6から改名)現行のブラウザで動かない場合も
- 2016年 ES2016 現行のブラウザでブラウザで動かない場合も
- 補足　ESとはECMAScriptの略。ECMAScriptとはJavaScriptの主な仕様を抜き出して標準化したもの。

2. はじめてのJavaScript<br>
console/log('Hello World!');
3. エラー解決<br>
[エラー一覧]https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference/Global_Objects/Error
4. コメント
- 1行の時 // コメントしたい文章
- 複数行の時 /* コメントしたい行１・２　*/
5. 演算(四則演算と余り)
- 足し算「+」 console.log(10 + 3);
- 引き算「-」 console.log(10 - 3);
- 掛け算「*」 console.log(10 * 3);
- 割り算「/」 console.log(10 / 3);
- 余り 「%」 console.log(10 % 3);
5. 変数
- データを一時的に保存できる入れもの
- 変数の宣言 var 変数名[=初期値]
6. インクリメントとデクリメント<br>
- x++ → x + 1 値に1を足す＝インクリメント
- x-- → x - 1 値から1を引く＝デクリメント
- 後置演算→x++,x--のように変数の後に++,--がつく記述の仕方
- 前置演算→++x,--xのように変数の前に++,--がつく記述の仕方
7. 条件分岐
- 「もし〇〇ならばxxする」
- if / else
- if / else if / else
- switch 対処となる1つの値を様々な値と比較して一致しているかどうか調べたい時に便利