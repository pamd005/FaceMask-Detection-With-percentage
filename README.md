# 😷 FaceMask Detection with Percentage Confidence

A deep learning-based project that detects whether a person is wearing a face mask and shows the **confidence percentage** using OpenCV and TensorFlow/Keras. Built using Python and Jupyter Notebook.

## 📌 Project Highlights

- 🔍 Detects faces in images or webcam feed
- ✅ Classifies as **"Mask"** or **"No Mask"**
- 📊 Displays **confidence percentage** for each prediction
- 📷 Works on images and real-time video

## 🛠️ Tech Stack

- Python 3.x
- TensorFlow / Keras
- OpenCV
- NumPy, Matplotlib
- Jupyter Notebook

## 📁 Files Included

- `Face_Mask_Detection.ipynb` – Notebook with training, model building, and real-time mask detection with percentage.
- `README.md` – Project overview and usage instructions.

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/pamd005/FaceMask-Detection-With-percentage.git
cd FaceMask-Detection-With-percentage
````

### 2. Install dependencies

```bash
pip install tensorflow opencv-python numpy matplotlib
```

> Or use a `requirements.txt` if added.

### 3. Run the notebook

```bash
jupyter notebook Face_Mask_Detection.ipynb
```

## 🖼️ Dataset

Use a dataset like:

* [Kaggle Face Mask Detection Dataset](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection)

Organize as:

```
dataset/
├── with_mask/
├── without_mask/
```

## 💡 How It Works

* The model is trained to detect whether the person is wearing a mask.
* During prediction (webcam or image), it draws a rectangle around the face and displays:

  * Classification: **Mask / No Mask**
  * Confidence Score (e.g., `Mask: 97.52%`)

## 📈 Results

* Achieved \~95% validation accuracy
* Real-time detection with confidence scoring
* Works well with multiple faces in frame

## 📷 Sample Output

> *(Add a screenshot here)*
> `<img src="output_sample.png" width="400"/>`

## ✅ Features

* Real-time mask detection
* High accuracy model
* Confidence display
* Lightweight and fast

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 🙌 Acknowledgements

* [Kaggle](https://www.kaggle.com/)
* TensorFlow Team
* OpenCV Contributors

---

👤 Developed by [**@pamd005**](https://github.com/pamd005)
