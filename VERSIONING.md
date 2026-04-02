# バージョニングルール

zeimu-ai Organization 配下の全リポジトリは [Semantic Versioning 2.0.0](https://semver.org/lang/ja/) に準拠します。

## バージョン体系

`MAJOR.MINOR.PATCH`

| 変更種別 | バージョン | 例 |
|---------|-----------|-----|
| バグ修正・小さな追加（既存構造のまま） | PATCH | 0.1.1 → 0.1.2 |
| 新フィールド追加・構造変更 | MINOR | 0.1.x → 0.2.0 |
| 破壊的変更（フィールド削除・リネーム） | MAJOR | 0.x → 1.0.0 |

## データリポジトリ（open-journal-rules）の具体例

| 変更内容 | バージョン |
|---------|-----------|
| ルール追加・修正（JSON構造変更なし） | PATCH |
| エビデンスURL追加・修正 | PATCH |
| 新フィールド追加（例: citations） | MINOR |
| フィールド削除・リネーム | MAJOR |

## コードリポジトリ（open-freee-demo-kit等）の具体例

| 変更内容 | バージョン |
|---------|-----------|
| バグ修正 | PATCH |
| 新コマンド・新機能追加 | MINOR |
| API破壊的変更 | MAJOR |

## 1.0.0 リリースの基準

- 実プロダクトで3ヶ月以上安定稼働
- 外部コントリビューターが利用開始
- JSONスキーマが安定（頻繁な構造変更がなくなった時点）

## CHANGELOG

全リポジトリで [Keep a Changelog](https://keepachangelog.com/ja/) 形式を使用します。
