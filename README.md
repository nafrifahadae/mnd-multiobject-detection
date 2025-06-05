## mnd-multiobject-detection
## 🧠 Facial Landmark Detection for MND Research (Inspired by Rob Burrow Centre)

This project is an early-stage exploration into how machine learning and computer vision might assist in the **early detection of Motor Neurone Disease (MND)** — specifically through **facial landmark analysis**. Inspired by research from the Rob Burrow Centre, it combines technical learning with a personal interest in healthcare innovation.


## ✅ Part 1: Image Preprocessing Pipeline

The current focus has been on building a **robust, automated image pipeline** to prepare facial data for later analysis and modelling.

### Key Highlights:
- 🖼️ Scaled and preprocessed images from FER2013 dataset
- 🔍 Detected facial landmarks and visualised feature points
- 💾 Saved processed images to a dedicated directory with dynamic filenames
- 🔁 Built reusable functions for automation and scalability

> Example filename: `subject3_landmarks_20250605_203515.png`

## 🔧 Tech Stack

- Python 3.10 (based on dlib compatibility)
- NumPy
- OpenCV (`cv2`)
- Matplotlib
- Pillow
- OS & datetime modules

## 🚧 Project Status

This project is **still in progress**. Part 1 is complete, focusing on building automated preprocessing and saving facial data .  

Next steps include:
- 📈 Building ML models in Part 2
- 🧪 Evaluating their potential in detecting early facial weakness
