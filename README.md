## Goods Detection and Description AI Agent

A Python-based AI agent that combines YOLOv8 and Qwen2-VL to detect goods in images and generate descriptions.

### Features
- **Goods Detection**: Uses YOLOv8 to identify and crop goods from images.
- **Description Generation**: Employs Qwen2-VL to describe the appearance and use of goods (non-living, non-food).

### Tech Stack
- **Detection Model**: YOLOv8 (pose task).
- **Vision-Language Model**: Qwen2-VL-2B-Instruct (description generation).
- **Tools**: PyTorch, Ultralytics, Transformers, OpenCV.

### Usage
1. Install: `pip install -r requirements.txt`.
2. Prepare YOLO weights (`s_best.pt`) and an image.
3. Run the script with an image path to get detection and description.

### Example
- Input: `/workspace/MVIMG_20230331_082423.jpg`
- Output: Bounding box + description (e.g., "This is a metal wrench used for tightening screws.")
- Result saved as `result.png`.



## 物體識別與描述 AI Agent

一個基於 Python 的 AI 代理，結合 YOLOv8 與 Qwen2-VL 模型，用於檢測圖片中的貨物並生成描述。

### 功能
- **貨物檢測**：使用 YOLOv8 識別圖片中的貨物並裁剪。
- **外觀描述**：透過 Qwen2-VL 生成貨物的外觀與用途描述（非生物或食物）。

### 技術
- **檢測模型**：YOLOv8（姿態檢測）。
- **視覺語言模型**：Qwen2-VL-2B-Instruct（生成描述）。
- **工具**：PyTorch、Ultralytics、Transformers、OpenCV。

### 使用
1. 安裝依賴：`pip install -r requirements.txt`。
2. 準備 YOLO 模型權重（`s_best.pt`）與圖片。
3. 執行程式，輸入圖片路徑，生成檢測框與描述。

### 範例
- 輸入：`/workspace/MVIMG_20230331_082423.jpg`
- 輸出：檢測框 + 描述（如「這是一個金屬扳手，用於擰緊螺絲。」）
- 結果保存為 `result.png`。



