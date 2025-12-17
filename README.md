天気連動型ファッション提案ボット (Weather-Linked Fashion Bot)

Difyを活用して構築した、都市名から天気を取得し、アパレル業界に身を置いていたプロとして最適な服装とアドバイスを提案するチャットボットです。

機能概要
1. 自然言語処理: ユーザーの入力から都市名を抽出 (LLM)
2. API連携: Open-Meteo APIよりリアルタイムの気象データを取得
3. ロジック判定: Pythonによる気温別の服装分岐 (Tシャツ/長袖/コート)
4. アドバイス生成: アパレル店員のペルソナによるスタイリング提案

使用技術
- Platform: Dify (Workflow)
- Language: Python (Data Processing)
- API: Open-Meteo API
- Model: Gemini無料版

ファイル構成
- `*.yml`: Difyワークフローの設計図（インポートして使用可能）
- `main.py`: ステップ4で使用している判定ロジックのソースコード
