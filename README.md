# 🖋️ Pencil Sketch Filter with Trackbars – OpenCV & Python

This project applies a pencil sketch effect to static images using Python and OpenCV, with real-time control through trackbars. Users can adjust the **blur intensity** and **gamma correction** to get different sketch styles. It's a great way to understand image processing fundamentals and GUI interaction in OpenCV.

## 📷 Features
- Converts any image to pencil sketch style
- Interactive control panel using OpenCV trackbars
- Adjustable `k_size` for blurring and `gamma` for contrast/brightness
- Real-time preview of adjustments

## 🧠 How It Works
1. The input image is converted to grayscale.
2. A Gaussian blur is applied to soften the grayscale image.
3. Image division enhances edges to simulate a pencil drawing.
4. Gamma correction is applied using a look-up table (LUT).
5. Trackbars allow dynamic adjustment of blur (`k_size`) and gamma.

## 🧰 Requirements
- Python 3.x
- OpenCV (`opencv-python`)
- NumPy

Install dependencies using:
```bash
pip install opencv-python numpy
