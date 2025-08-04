# 📸 Face Detection in Images using OpenCV

This simple Python project demonstrates how to detect faces in an image using **OpenCV** and the **Haar Cascade Classifier**. It reads an input image, processes it, detects any faces present, and displays the result with rectangles drawn around the detected faces.

---

## 🚀 Features

* Loads and resizes input images
* Converts image to grayscale
* Uses pre-trained `haarcascade_frontalface_default.xml` classifier
* Detects multiple faces in the image
* Draws blue rectangles around detected faces
* Displays the final result using OpenCV GUI window

---

## 🧰 Tech Stack

* `Python`
* `OpenCV`

---

## 📂 Project Files

```
📁 face-detection/
├── facerecognition.py                    # Main face detection script
├── 3.png                             # Sample image with faces
├── haarcascade_frontalface_default.xml # Haar Cascade model file
└── README.md
```

---

## 📌 How to Run

1. **Install OpenCV:**

```bash
pip install opencv-python
```

2. **Ensure the following are present in the project folder:**

   * `facerecognition.py` (your script)
   * `3.png` (or any image you want to test)
   * `haarcascade_frontalface_default.xml`

3. **Run the script:**

```bash
python facerecognition.py
```

4. **Output:**

   * A window will appear showing the image with blue rectangles around any detected faces.
   * Press any key to close the image window.

---

## 💡 Notes

* If no faces are detected, try with a clearer or larger image.
* The resize factor can be adjusted using `fx` and `fy` in `cv2.resize()`.
* You can change the image file name to load different test images.

---

## 📜 License

This project is available under the [MIT License](LICENSE).
