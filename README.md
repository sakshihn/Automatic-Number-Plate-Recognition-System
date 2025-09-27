# 🚗 Automatic Number Plate Recognition (ANPR)

A Python-based **Automatic Number Plate Recognition (ANPR)** system implemented in a **Jupyter Notebook** using **OpenCV** and **Tesseract OCR**.
The project detects number plates from images, extracts the plate region, and recognizes the alphanumeric text automatically.

---

## 📌 Features

* Detects number plates from input images
* Extracts text from plates using OCR
* Simple Jupyter Notebook workflow for experimentation
* Includes sample images for testing

---

## 📂 Repository Structure

```
ANPR-Project/
│── ANPR.ipynb          # Jupyter Notebook implementation
│── README.md           # Documentation
│── LICENSE             # MIT License
│── .gitignore          # Ignored files
│── image1.jpeg         # Sample image
│── image2.jpg          # Sample image
│── image3.jpeg         # Sample image
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/ANPR-Project.git
cd ANPR-Project
```

Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

Ensure [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) is installed and added to PATH.

---

## ▶️ Usage

Open the notebook:

```bash
jupyter notebook ANPR.ipynb
```

Run the cells step by step.
You can replace the provided sample images with your own test images.

---

## 🚀 Future Improvements

* Improve plate detection with advanced object detection models (YOLO, Faster-RCNN)
* Use deep learning-based OCR for higher accuracy
* Extend to real-time video or webcam-based ANPR
* Integrate with a backend database for vehicle tracking

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
