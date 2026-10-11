# Luqnexa

「最小の容量で、最大の語彙を、最速で、最高精度に。」

Rustを中心に開発するOSSのIMEプロジェクトです。通常変換をオフラインで動かし、任意の端末内AIで文脈に合う候補を選びます。

| リポジトリ | 内容 | 現状 |
|---|---|---|
| [Luqnexa](https://github.com/Luqnexa/Luqnexa) | IME・CLI・Windows TSF | 共通コアとWindows試作版 |
| [NEXC](https://github.com/Luqnexa/NEXC) | 独自圧縮・ディスク検索・追記辞書 | 研究用プロトタイプ |
| [Luqnexa-AI](https://github.com/Luqnexa/Luqnexa-AI) | 文章理解・候補順位づけ・ケース選択 | 端末内モデル接続・軽量学習、自由生成は未実装 |
| [Luqnexa-Server](https://github.com/Luqnexa/Luqnexa-Server) | 公開文章収集・将来の辞書配信 | 収集スクリプト、配信APIは未実装 |

1億エントリ・1GiB以下・iPhone SEでp95 5msという目標は未達成または未検証です。測定条件を示し、実測値以外の性能比較を行いません。入力の外部送信・返信の自動送信は行いません。

本体・圧縮エンジン・AI接続・収集ソースはAGPL-3.0-onlyです。第三者の辞書・モデル・コーパスには各配布元の条件を保持します。
