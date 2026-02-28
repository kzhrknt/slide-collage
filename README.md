# Slide Collage

複数のスライド画像から1枚のコラージュ画像を生成するWebツール

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/kzhrknt/slide-collage)

## 🎨 Demo

**https://slide-collage.vercel.app/**

## ✨ Features

- **グリッドレイアウト自動調整** - 最大30枚のスライドをグリッド配置
- **柔軟なカスタマイズ**
  - 列数・間隔・外側余白の調整
  - 列ずらし（偶数列を縦方向にオフセット）
  - 全体の回転（-45° 〜 +45°）
  - ズーム（100% 〜 300%）
- **スライド単位のぼかし機能** - 機密情報を含むスライドをワンクリックでぼかし
- **ぼかし強度調整** - 0px 〜 30px で調整可能
- **高解像度出力対応** - フルHD / 2K / 4K / カスタムサイズ
- **サンプルスライド付き** - 初回訪問時に30枚のサンプル画像を自動生成
- **完全クライアントサイド** - 画像はブラウザ内で処理、サーバーに送信されません
- **SNSシェア** - Xで簡単にシェア

## 🚀 Usage

1. スライド画像をドラッグ&ドロップ、またはファイルを選択
2. グリッド・レイアウトを調整
3. 機密情報を含むスライドには🔒ボタンでぼかしを適用
4. PNG/JPGで書き出し

## 🛠 Tech Stack

- HTML5 / CSS3 / JavaScript (Vanilla)
- Canvas API
- Vercel (Hosting)

## 💡 Motivation

スライド稼業の我々としては、登壇資料がポートフォリオの一部になってくるわけですが、「グリッドで並んだ画像を作る」「機密情報をぼかす」といった作業が地味に面倒だったので、このツールを作りました。

## 📦 Local Development

```bash
# Clone repository
git clone https://github.com/kzhrknt/slide-collage.git
cd slide-collage

# Open in browser
open index.html
```

シンプルな静的HTMLファイルなので、ビルドプロセスは不要です。

## 📄 License

MIT License

## 👤 Author

[@kzhrknt](https://github.com/kzhrknt)

## 🤝 Contributing

Issues and Pull Requests are welcome!

---

Made with Claude Code ☕
