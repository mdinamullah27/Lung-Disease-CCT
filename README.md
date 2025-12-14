<h1 align="center">
  🩺 An effective approach to address processing time and computational complexity  
  employing Modified CCT for Lung Disease Classification
</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=Medical%20AI%20%7C%20Chest%20X-ray%20Classification;Modified%20Compact%20Convolutional%20Transformer;Lightweight%20&%20Efficient&center=true&width=650&height=45">
</p>

---

## 📘 Paper Details

- **Authors:** Inam Ullah Khan, Sami Azam, Sidratul Montaha, Abdullah Al Mahmud, A.K.M. Rakibul Haque Rafid, Md Zahid Hasan & Mirjam Jonkman :contentReference[oaicite:1]{index=1}  
- **Journal / Year:** Intelligent Systems with Applications (2022) :contentReference[oaicite:3]{index=3}  
- **DOI:** `10.1016/j.iswa.2022.200147` :contentReference[oaicite:4]{index=4}  
- **Article Link / PDF:** [Publisher Version / PDF] — (add link here if you have)  

---

## 🎯 Objective  

Early diagnosis of lung diseases from X-ray images often suffers from two key issues:

- Imbalanced and insufficient medical image datasets.  
- High computational cost (training time) when using high-resolution images or heavy models. :contentReference[oaicite:5]{index=5}  

This work proposes a solution: a **Modified Compact Convolutional Transformer (MCCT)** model that reduces input image size (32 × 32), applies robust preprocessing & augmentation (GAN-based balancing, noise/artifact removal, contrast/brightness enhancement), and achieves **fast, accurate lung disorder classification into four classes** — while drastically cutting down training time. :contentReference[oaicite:6]{index=6}

---

## 🧠 Methodology & Key Components  

- Image preprocessing: artifact removal, noise reduction, contrast/brightness adjustment  
- Data balancing: Synthetic image generation using GAN (DCGAN) to compensate for class imbalance :contentReference[oaicite:7]{index=7}  
- Model: Modified Compact Convolutional Transformer (MCCT), using 32×32 images for efficiency  
- Baseline comparison: Trained and compared six transfer-learning models (VGG16, VGG19, ResNet50, ResNet152, ResNet50V2, MobileNet) under identical conditions — MCCT outperformed in both accuracy and speed. :contentReference[oaicite:8]{index=8}  

---

## 📊 Results  

- ✅ Test accuracy: **95.37%** with MCCT. :contentReference[oaicite:9]{index=9}  
- ✅ Training time: ~ 10–12 s/epoch for MCCT vs ~ 80–90 s/epoch for baseline models. :contentReference[oaicite:10]{index=10}  
- ✅ Even with reduced dataset size (from ~49,621 images down to ~6,204), the performance remains stable — demonstrating robustness under data scarcity. :contentReference[oaicite:11]{index=11}  


---

## 📝 How to Use / Reproduce  


Preprocess data (artifact removal, normalization, augmentation / GAN balancing)  
Train MCCT model (on 32×32 images) or evaluate using pretrained weights (if provided)  
Evaluate and compare results with baseline models  

---

📬 Contact / Links

🔗 ResearchGate Profile: https://www.researchgate.net/profile/Inam-Ullah-Khan-2

🧑‍💻 GitHub: https://github.com/mdinamullah27

📧 Email: inamkhan.me@gmail.com

## 📚 Citation  

If you use this work, please cite:

```bibtex
@article{khan2022effective,
  title   = {An effective approach to address processing time and computational complexity employing Modified CCT for Lung Disease Classification},
  author  = {Khan, Inam Ullah and Azam, Sami and Montaha, Sidratul and Al Mahmud, Abdullah and Rafid, A.K.M. Rakibul Haque and Hasan, Md Zahid and Jonkman, Mirjam},
  journal = {Intelligent Systems with Applications},
  year    = {2022},
  volume  = {16},
  pages   = {200147}
}
