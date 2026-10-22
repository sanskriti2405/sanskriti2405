<h1 align="center">Hi, I'm Sanskriti Goel 👋</h1>
<h3 align="center">AI undergrad building computer vision & NLP systems that explain their decisions</h3>

<p align="center">
  🎓 BSc (Hons) Artificial Intelligence · NMIMS, Navi Mumbai
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sanskriti-goel5/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

---

### 🧠 About me

- I build **end-to-end ML projects**: data pipelines, training, honest evaluation and a working demo.
- Most of my recent work is in **media forensics**: detecting forged documents and deepfake videos.
- I care about **explainability and honest metrics**. Every project here reports its limitations next to its results.

---

### 🔎 Featured: [DocuGuard](https://github.com/sanskriti2405/docuguard)

**Detects invisible forgeries in scanned documents** (marksheets, invoices, certificates, ID cards, application forms) and explains *what* was changed, *how*, and *why you can't see it*.

**87% accuracy · 0.93 ROC-AUC · 0.79 pixel F1 · ~2 s per page on CPU**, measured on document designs never seen in training.

- Built a **synthetic forgery generator** that imitates a careful human forger, covering retype, copy-move, splice, erasure and insertion.
- Designed a **0.8M-parameter ForensicUNet** that reads noise residuals and JPEG-ghost channels at full resolution. It is exported to **ONNX** and runs on a laptop.
- Combined it with **OCR + arithmetic checks** (qty × price = amount, marks → total) and **gradient boosting / random forest** stages.
- Every finding comes with **plain-English evidence**, e.g. *"scanner noise here is 42% weaker than on the rest of the page"*.

`PyTorch` `OpenCV` `ONNX Runtime` `scikit-learn` `RapidOCR`

---

### 🛠️ Projects

| Project | What it does | Result | Stack |
|---|---|---|---|
| [**DocuGuard**](https://github.com/sanskriti2405/docuguard) | Explainable forgery detection for scanned documents | 87% acc · 0.93 AUC on unseen templates | PyTorch · OpenCV · ONNX · scikit-learn |
| [**Deepfake Video Detection**](https://github.com/sanskriti2405/deepfake-video-detection) | MTCNN face extraction + DenseNet121 on FaceForensics++ *(team project, compared with ResNet50 and VGG19)* | 94.8% acc · 0.989 AUC (DenseNet121) | TensorFlow · OpenCV · MTCNN |
| [**Traffic Sign Recognition**](https://github.com/sanskriti2405/traffic-sign-recognition-cnn) | Custom 231K-parameter CNN for 43 GTSRB classes, with a Gradio demo | 99.3% hold-out accuracy | TensorFlow · OpenCV · Gradio |

---

### 🧰 Tech stack

**Languages:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Deep learning:**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white)

**ML & data:**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)

**Computer vision:**
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![MTCNN](https://img.shields.io/badge/MTCNN-555555?style=flat)

**Tools:**
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat&logo=gradio&logoColor=white)

