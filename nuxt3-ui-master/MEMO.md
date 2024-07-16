# 学習メモ
## 環境設定(bun)
・JavaScriptおよびTypeScriptを実行、構築、テストするためのオールインワンのツール
・npmと互換性があり、Node.jsやnpmよりも高速で動作することが特徴

*ターミナルに下記コードを入力してから使用できる
`` Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process``
【感想】
・npmより速い気がする
・run終了時、Control+Cのみで終了できる(npmはControl+C→Y)
## grid(グリッド)とは？
・列と行を定義する水平線と垂直線の集合が交差したもの
・要素をグリッド上の行と列の中に配置することができる
https://developer.mozilla.org/ja/docs/Web/CSS/CSS_grid_layout/Basic_concepts_of_grid_layout

## つまづき1（未解決）6/24
``` app.config.ts ```内のCSSが反映されない。
``` <UButton>Button</UButton> ```は別途設定が必要みたい。
https://ui.nuxt.com/getting-started/theming

## つまづき1（解決）6/24
何もせずに解決していた。
今度エラーでたら、サーバー立ち上げ直してみるといいかも。