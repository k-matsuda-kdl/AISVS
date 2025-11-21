# OWASP 人工知能セキュリティ検証標準 (AISVS)

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

この作品は
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa]の下でライセンスされています。

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-blue.svg

## はじめに

人工知能セキュリティ検証標準（AISVS）は、開発者、アーキテクト、セキュリティ専門家に、AI駆動型アプリケーションのセキュリティと倫理的考慮事項を評価および検証するための構造化されたチェックリストを提供することに焦点を当てています。既存のOWASP標準（Webアプリケーション用のAISVSなど）をモデルにしたAISVSは、以下の分野の要件カテゴリを定義します：

1. [トレーニングデータのガバナンスとバイアス管理](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C01-Training-Data-Governance.md)
2. [ユーザー入力の検証](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C02-User-Input-Validation.md)
3. [モデルライフサイクル管理と変更管理](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C03-Model-Lifecycle-Management.md)
4. [インフラストラクチャ、設定、デプロイメントのセキュリティ](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C04-Infrastructure.md)
5. [アクセス制御とアイデンティティ](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C05-Access-Control-and-Identity.md)
6. [モデル、フレームワーク、データのサプライチェーンセキュリティ](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C06-Supply-Chain.md)
7. [モデルの動作、出力制御、安全性保証](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C07-Model-Behavior.md)
8. [メモリ、埋め込み、ベクトルデータベースのセキュリティ](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C08-Memory-Embeddings-and-Vector-Database.md)
9. [自律オーケストレーションとエージェントアクションのセキュリティ](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C09-Orchestration-and-Agentic-Action.md)
10. [敵対的ロバスト性と攻撃耐性](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C10-Adversarial-Robustness.md)
11. [プライバシー保護と個人データ管理](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C11-Privacy.md)
12. [監視、ロギング、異常検出](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C12-Monitoring-and-Logging.md)
13. [人間による監視と信頼](https://github.com/OWASP/AISVS/blob/main/1.0/ja-JP/0x10-C13-Human-Oversight.md)

**バグを見つけた場合やアイデアがある場合は、[issueを記録](https://github.com/OWASP/ASIVS/issues)してください。issueでの議論に基づいて、[プルリクエストを開く](https://github.com/OWASP/AISVS/pulls)ようお願いすることがあります。**

## プロジェクトリーダー

このプロジェクトは、2人のプロジェクトリーダー[Jim Manico](https://github.com/jmanico)と[Russ Memisyazici](https://github.com/vtknightmare)によって主導されています。

## ライセンス

プロジェクト全体のコンテンツは、**[Creative Commons Attribution-Share Alike v4.0](https://creativecommons.org/licenses/by-sa/4.0/)**ライセンスの下にあります。
