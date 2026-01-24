# app

Python プロジェクトのテンプレートです。

## 必要条件

- Python 3.12 以上
- [uv](https://github.com/astral-sh/uv) (パッケージマネージャー)

## セットアップ

### Dev Container を使用する場合（推奨）

1. VS Code で [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) 拡張機能をインストール
2. このリポジトリをクローン
3. VS Code でフォルダを開き、「Reopen in Container」を選択

### ローカル環境の場合

```bash
# 依存関係のインストール
uv sync

# 仮想環境を有効化
source .venv/bin/activate
```

## 実行

```bash
python main.py
```

## 開発

- **フォーマッター**: Black
- **リンター**: Ruff

ファイルを保存すると自動的にフォーマットされます。

## ライセンス

[MIT License](LICENSE)
