# Scrap Launcher for ScrapMechanic v0.5.0

Scrap Launcher for ScrapMechanic（SL4SM）のマルチプレイ連携とサバイバル補助機能をまとめたリリースです。

## 追加・改善

- マルチプレイ向けの「接続サーバー」「プロファイル・起動」「テレポート地点」を追加
- ホストの機能設定を共有し、参加者が同じ設定を適用してSteam経由で起動できるように改善
- 共有地点ネットワークに、サーバー作成・サーバーID追加・管理権限・検索・地点登録を実装
- `/vector3` で現在地を整数座標として取得できるように改善
- `/tp x,y,z` 実行時に、地面へ埋まりにくいよう着地点を上方へ補正
- Blueprint Placement を公式の設計図選択画面とリフト操作に統合
- Levitation の操作性を改善
  - `/levitation true` で有効化
  - `Shift`で飛行、Shiftを離して空中停止、`Ctrl`で終了
  - 飛行中と終了直後は落下ダメージから保護
- ダッシュボード、機能設定、コマンド集、マルチプレイ画面の導線と表示を整理
- 旧バージョン互換用のCreative Lift設定を削除し、Blueprint Placementへ一本化
- ゲーム buildid の日次変動によって同期できなくなる判定を緩和

## 重要な注意

- 本ソフトウェアはゲームのサバイバル用 Lua ファイルを変更します。設定の切り替えはゲームを終了してから行ってください。
- マルチプレイでは、ホストと参加者で設定が異なるとチェックサムエラーとなる場合があります。「プロファイル・起動」からホスト設定を適用してください。
- Scrap Mechanicのアップデート後は、ゲーム側の構造変更により対応版を待つ必要が生じる場合があります。

## 配布物

- `ScrapLauncherForScrapMechanicSetup_0.5.0.exe`
- `SHA256SUMS.txt`
- `ScrapLauncherForScrapMechanicSetup_0.5.0.exe.sha256`

## SHA-256

```text
00EE767A4E5BEAFEFAD586C03FC4A9AD49635EBDA0332AD6C462CD13759AC709  ScrapLauncherForScrapMechanicSetup_0.5.0.exe
```
