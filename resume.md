# 職務経歴書



## 職務経歴

### ソーシャルゲーム開発会社(2012/03 ~)

#### インフラチーム(2016/03 ~)

プロジェクト規模: 2 ~ 5 人
使用技術: AWS CloudFormation, Ansible, Go, AWS の各種サービス

- ゲームの安定リリース・運用, また構築コスト削減
  - インフラ構築自動化と共通化
    - 口伝・手作業になっていたもののコード化から着手し, CloudFormation・Ansible による自動化を行った
    - オートスケーリングや, AWS の AutoRecover, システムの改修を行い, SPOF となっているサーバーの排除も行なった 
    - 自動化・共通化また上記の SPOF 排除の過程で, これまでのデプロイ方法の刷新が必要になったため CodeDeploy の導入
  - 安定化に伴いデプロイ方法の刷新が必要となったため, AWS CodeDeploy の導入
  - CloudFormation template への入力パラメーターをコード化するためのツールを Go で開発
  - 現在(2019/01)半分くらいのプロジェクトで導入・運用中
- AWS を利用したゲーム開発チームが利用できるマイクロサービスの開発
  - 期限付き HLS 配信サービス
  - クライアントから HTTP で送られてくるログの収集サービス

#### 新卒教育(2017/01~)

- 入社してから１年間の基礎教育
  - 一年後にソーシャルゲーム開発チームにスムーズに配属できるよう教育を行った
  - 基礎知識取得のための課題作成
    - git の操作, インフラ, Python/Django, Unity
  - 新卒 1 名を受け持ち OJT 担当

#### ソーシャルゲーム開発(2012/03 ~ 2016/02)

主な使用技術・ツール: Python2.7, PyPy2.7, Django1.x, Lua(クライアントサイドで利用), MySQL5.6, Redis2.x, New Relic

- 運用中ソーシャルゲームの技術的負債の改修, その後運用・開発(2015/04 ~ 2016/02)
  - サーバーサイドのマイナーバグや開発用ツールの不便さ・レスポンス速度の悪化などの改修・改善
    - django-test にてバグの再現, MySQL のクエリーチューニング, ロジック最適化等
  - Cocos2d-x + Lua を利用しており, Lua によるクライアントサイド開発
    - こちらは UI 作成と API つなぎこみ程度
- 台湾支社開発ソーシャルゲームの開発サポート(2015/02 ~ 2015/05)
  - Python/Django で開発していたため, 本社利用の boilerplate に乗せ替え
  - Test の拡充とバグ修正
  - 支社側エンジニアとのチャット越しにやりとりしつつ進行
    - ビデオチャット・出張の際は通訳してもらった
- 新規ソーシャルゲーム開発2(2014/03 ~ 2015/01)
  - 2(2014/03 ~ 2015/01)
    - クライアントサイドのエンジン選定を外注会社と共同で検証
      - Unreal Engine, Unity, Cocos2d-x
    - リリースされず開発終了
- 不適切文字列検証サービス開発(2014/03 ~ 2014/08)
  - 既に中央基盤システムとしてユーザー入力文字列を管理しており, そこへの追加機能という形で開発
    - ElasticSearch で定期的に不適切な文字列を抽出, それを人間がチェックするシステム
      - AWS Kinesis, AWS DynamoDB, ElasticSearch, Python/Django, MySQL 
      - (今だったら AWS のサービスを組み合わせてもっとうまくできそう・・・)
- 新規ソーシャルゲーム開発1(2013/08 ~ 2014/02)
  - 1(2013/08 ~ 2014/02)
    - サーバーサイド(Python/Django)・管理画面の開発のみ
      - サーバーサイドエンジニアは 1 ~ 2 人
    - リリース後別のプロジェクト異動のため, 引き継ぎ
- フィーチャーフォン・スマートフォンのブラウザ向けソーシャルゲーム運用・開発(2013/03 ~ 2014/02)
  - 新卒で配属
  - Python/Django, jQuery


## 使用技術

- AWS
  - EC2, RDS, ElastiCache, KinesisStreams, DynamoDB, ...
  - ECS, Fargate(社内ツールとしてのみ利用)
  - CloudFormation, ServiceCatalog, SystemsManager
  - CodeDeploy, CodeBuild
  - Lambda, API Gateway
- GCP
  - BigQuery
- OS
  - Ubuntu14.04, 16.04, 
- 監視ツール
  - Zabbix, mackerel
  - Prometheus(検証のみ)
- プログラム言語
  - Python2.7, PyPy2.7
  - Go
  - Lua
- ミドルウェア
  - Nginx, OpenResty
  - uwsgi
  - td-agent2, 3
- CI
  - GitLab CI/CD
  - Jenkins
- フロントエンド
  - Cocos2d-x Lua binding
  - Unity(個人学習のみ)
  - React, Redux(どちらも個人学習のみ)
- その他
  - ElasticSearch
  - RabbitMQ
  - Docker

