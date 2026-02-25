# 🎨 Task 05 – Neural Style Transfer

## 📌 Project Overview

This project demonstrates Neural Style Transfer using Deep Learning.

Neural Style Transfer is a technique that combines:
- The **content** of one image
- The **style** (texture, colors, brush strokes) of another image

to generate a new stylized image.

In this project, the artistic style of a painting is applied to a real-world image using a pre-trained deep learning model.

---

## 🧠 Objective

To apply the artistic style of one image to the content of another image using Neural Networks (CNN).

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- TensorFlow Hub
- Pretrained VGG19-based Model
- Google Colab

---

## ⚙️ How It Works

1. The content image and style image are loaded.
2. A pre-trained convolutional neural network (CNN) extracts:
   - Content features from the content image
   - Style features from the style image
3. The model combines both features.
4. A new image is generated that:
   - Preserves the structure of the content image
   - Adopts the artistic texture and colors of the style image

---

## 📷 Input Images

- Content Image: Taj Mahal (example)
- Style Image: Van Gogh-style painting (example)

---

## 🖼️ Output

The final output image maintains the structure of the Taj Mahal while applying the brush strokes and artistic texture of the painting.

---

## 🚀 Key Concepts

- Convolutional Neural Networks (CNN)
- Feature Extraction
- Content Loss
- Style Loss
- Gram Matrix
- Generative Deep Learning

---

## 📌 Conclusion

Neural Style Transfer successfully merges artistic styles with real-world images using deep learning.  
This project demonstrates how pre-trained models can be used to generate creative and visually appealing outputs.

---

## 📖 References

- TensorFlow Style Transfer Tutorial
- Towards Data Science Article on Neural Style Transfer
- GeeksforGeeks Deep Learning Guide
