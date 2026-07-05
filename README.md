# 決済ナビ（payment-navi）

個人店・小規模店向けの、**完全中立**なキャッシュレス決済 比較診断サイト。店舗（対面）とネットショップ（EC）の両方に対応。

- 広告・優先表示なし。順位は利用者の入力条件のみで機械的に算出
- 店舗（対面）とEC（オンライン）でチャネル別に診断 →「年間コスト目安」を年間取扱高から実額試算
- 店舗端末 主要10社（Square / Airペイ / STORES決済 / stera pack / 楽天ペイ / PayPay / USEN PAY / スマレジ・PAYGATE / おてがるPay / Times PAY）
- EC決済 主要12サービス（BASE / STORES / Shopify / Square / Stripe / PayPal / GMOイプシロン / KOMOJU 等。カート型・リンク型・決済代行の3トラック）
- 導入状況×取扱高（2億円ボーダー）で「そのまま導入／申込」↔「無料相談」を出し分け

## 構成

- `index.html` … 単一ファイル・依存なし。ブラウザで開くだけで動作。データは `SERVICES` / `EC_SERVICES` 配列に集約
- `guide.html` … 「こんなお店なら→これ」早見ガイド（noindex）
- `privacy.html` … プライバシーポリシー
- `.nojekyll` … GitHub Pages の Jekyll ビルドを無効化（静的配信）
- 掲載の料率・費用は参考値（2026年7月時点）。契約前に各社公式で要確認

## ローカルで確認

`index.html` をブラウザで開くだけ。

## 公開

GitHub Pages（main / ルート）で配信。
