# BuildTFT - TFTダメージシミュレータ

TFT（Teamfight Tactics）のダメージ計算、ステータス計算、装備シミュレーションを行うためのデスクトップアプリケーションです。
戦闘は1v1を想定しており、アタッカーがターゲットに与えるダメージを詳細に可視化し、最適なビルドの検証に役立ちます。

---

## 📥 インストール方法（Windows）

1. [Releases ページ](https://github.com/meteoji/BuildTFT/releases) にアクセスします。
2. 最新のリリース（例: `v0.1.0`）から **`BuildTFT Setup 0.1.0.exe`** をダウンロードします。
3. ダウンロードした `.exe` ファイルを実行すると、セットアップウィザードが起動します。画面の指示に従ってインストールを完了してください。

> [!NOTE]
> **Windows SmartScreen やウイルス対策ソフトによるブロックについて**
> 本アプリは個人開発かつデジタル署名を購入していないため、起動時に「WindowsによってPCが保護されました」等の警告が表示される場合があります。
> 安全性には問題ありませんので、画面内の「**詳細情報**」をクリックし、「**実行**」ボタンを押して進めてください。

---

## ✨ 主な機能

* **チャンピオンのステータス計算**: アイテム、特性、スキル効果などを加味した実数値の算出。
* **詳細なダメージ計算**: 通常攻撃やスキルがターゲットに与えるダメージ、防御ステータスによる軽減、負傷・細断などのデバフや行動阻害（CC）の影響をシミュレート。
* **ビルド検証**: アイテムや特性の組み合わせごとの戦闘時間あたりのDPS比較。
* **自動アップデート**: アプリ起動時にバックグラウンドで自動的にアップデートが検知・適用されます（手動で毎回インストーラーをダウンロードし直す必要はありません）。

---

## 🖥️ 動作環境

* **対応OS**: Windows 10 / 11 (64bit)

---

## ⚠️ 免責事項
* BuildTFT isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
* ダメージやステータスの計算結果は実際のゲーム内挙動と一致するよう最善を尽くしていますが、ゲームのアップデートや複雑なシナジーの状況により実際のゲーム内と若干の誤差が生じる場合があります。予めご了承ください。
