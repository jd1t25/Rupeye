# 🪙 Rupeye:

Detects INR coins using Yolo11 

---

## ⚙️ Key Operations

1. ✅ **Check GPU availability**  
   Ensures that Colab's GPU runtime is active using:

   ```python
   !nvidia-smi
   ```

2. 🔗 **Mount Google Drive**  
   Access and store datasets or model outputs using:

   ```python
   from google.colab import drive
   drive.mount('/content/gdrive')
   ```

---

## 🖼️ Dataset

> Crafted custom data by adding real-time pictures and painstakingly annotated them using **Roboflow** and **LabelImg**.

📂 Dataset Link:  
[🔗 Indian Rupees INR with Annotations (Kaggle)](https://www.kaggle.com/datasets/mayureshsaitwal/indian-rupees-inr-with-annotations/data)

---

## 💡 Usage

Use this notebook in **Google Colab** to:

- Access and explore annotated INR coin datasets
- Prepare training/validation datasets
- Interface with Roboflow-exported formats (e.g., YOLO, COCO)

---

## 📂 Outputs

| Image 1 | Image 2 |
|---------|---------|
| ![1](output/1.jpg) | ![2](output/2.jpg) |

---

## 📄 License

This notebook is provided under the MIT License.  
Use freely with proper attribution.
