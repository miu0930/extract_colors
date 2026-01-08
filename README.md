# Image Color Palette Extractor 🎨

画像から主要な色（ドミナントカラー）を抽出し、その比率を示すドーナツグラフとカラーコード（HEX）のパレットを生成するPythonツールです。デザインの配色分析や、画像の雰囲気（ムード）を可視化するのに最適です。

## 📸 Output Example

生成される画像のイメージ:
- **左側:** 色の分布を示すドーナツグラフ（中央に元画像）
- **右側:** 抽出された色の一覧とHEXコード
<img width="1600" height="1200" alt="sample jpg_color" src="https://github.com/user-attachments/assets/4dc8c319-2ac4-4cd5-ba91-b38eab7851c4" />

## 🛠️ Requirements

以下のライブラリを使用しています。

- Python 3.x
- pandas
- matplotlib
- extcolors
- colormap
- Pillow (PIL)
