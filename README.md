# アプリワン (app_one)

ボタンを押すと「helloWorld」と表示され、押した回数をカウントするFlutterアプリです。

## 機能

- 中央のボタンを押すと「helloWorld」が表示されます
- ボタンを押した回数がカウントされます
- リセットボタンでカウントを0に戻せます
- アニメーション効果とモダンなUIデザイン

## Android APKのダウンロード方法

### GitHub Actionsからダウンロード

1. [GitHubリポジトリ](https://github.com/yutackey/test1)にアクセス
2. 「Actions」タブをクリック
3. 最新のビルド（緑のチェックマーク）をクリック
4. 「app-release-apk」アーティファクトをダウンロード
5. ダウンロードしたAPKファイルをAndroidスマホに転送
6. スマホでAPKファイルを開いてインストール

### 手動でビルドを実行する場合

1. リポジトリの「Actions」タブに移動
2. 左側の「Build Android APK」を選択
3. 「Run workflow」ボタンをクリック
4. ビルドが完了したら、上記の手順でAPKをダウンロード

## ローカルでビルドする場合

```bash
# 依存関係をインストール
flutter pub get

# Android APKをビルド
flutter build apk --release

# ビルドされたAPKは以下にあります
# build/app/outputs/flutter-apk/app-release.apk
```

## 開発環境

- Flutter SDK: 3.24.0以上
- Dart SDK: 3.9.2以上

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
