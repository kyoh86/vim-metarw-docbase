# vim-docbase

DocBaseをVimで編集できるようにするプラグイン。

## 必要な依存プラグイン

* [vim-metarw](https://github.com/kana/vim-metarw)
* [vim-docbase](https://github.com/kyoh86/vim-docbase)

## 設定項目

[vim-docbase](https://github.com/kyoh86/vim-docbase) の設定を参照してください。

## 編集方法

* `:e docbase:`
  * 設定されたドメインの一覧を表示する。
* `:e docbase:[domain]:`
  * 指定したドメインの投稿の一覧を表示する。
* `:e docbase:[domain]:new:`
  * 指定したドメインの新しい投稿を作成する。
* `:e docbase:[domain]:<post-id>:`
  * 指定したドメインの指定の投稿を編集する。

## コマンド

`:Edit`, `:Read`, `:Source`, `:Write` の4つのコマンドを定義するには、

```vim
call metarw#define_wrapper_commands(v:true)
```

を呼び出します。
詳細は [vim-metarw](https://github.com/kana/vim-metarw) のヘルプを参照してください。

# LICENSE

[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg)](http://www.opensource.org/licenses/MIT)

This software is released under the [MIT License](http://www.opensource.org/licenses/MIT), see LICENSE.
