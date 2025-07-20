# 🖼️ Photorealistic Person Compositing with ShadowGAN

This project creates **realistic image composites** by placing a person into a background and generating **natural-looking shadows** using GANs. It ensures seamless blending and photorealism through shadow synthesis and edge refinement.

---

## 🔰 Input and Output Images

### 🎯 Input Images
- `person.jpg` → Image of person (with background)
- `back.png` → Target background image

### ✅ Output Image
- `final_composite.png` → Final result with person, background, and shadow

| Person Image | Background Image | Final Output |
|--------------|------------------|---------------|
| ![](person.jpg) | ![](back.jpg) | ![](final.jpg) |

---

## 🔄 Flowchart Overview

The entire process is summarized in the diagram below:

![Compositing Flowchart](chart1.jpg)

> 📌 *The flowchart shows major steps: background removal → light estimation → shadow generation → blending → refinement.*

---



## 📁 Files in Repo

