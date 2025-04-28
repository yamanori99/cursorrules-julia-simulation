# Juliaによるシミュレーション開発のためのCursorルール

このリポジトリは、Juliaを使ったシミュレーション開発プロジェクトのテンプレートであり、Cursorカスタムインストラクションを含みます。

## 概要

Julia言語を用いた効率的なシミュレーション開発を支援するためのCursorルールを提供します。必要に応じてPythonやRを用いた分析も想定しています (まだ未実装)。

このリポジトリは [kinopeee/cursorrules](https://github.com/kinopeee/cursorrules) を元に作成されており、詳細やオリジナルの情報についてはそちらも参考にしてください。

## Cursor用カスタムインストラクション

`.cursor/rules/global.mdc` に、Cursor IDEで効率的に開発を進めるためのカスタムインストラクションが含まれています。Cursor 0.45以降のProject Rules形式に対応しています。

特に、研究用途を想定し、日本語テキストの記述においてAPAスタイルに準拠するよう、句読点、読点、カギ括弧以外の全角記号、全角数字、全角スペースの使用を制限するルールを追加しています。

## セットアップ

1. このテンプレートリポジトリを元に、新しいリポジトリを作成します。
2. Cursorの設定画面 > 「Rules」タブで「Project Rules」を有効にします。
3. `technologystack.md` と `directorystructure.md` をプロジェクトの状況に合わせて編集します。

## 注意事項

- Rules for AIに矛盾する指示や大量の記載があると効果が減少する可能性があります。Rules for AIの記載内容をご確認ください。
- `technologystack.md` と `directorystructure.md` の内容は、ご自身のプロジェクトに合わせて適宜修正してください。

## ライセンス

MITライセンスの下で公開されています。詳細については[LICENSE](LICENSE)ファイルを参照してください。
