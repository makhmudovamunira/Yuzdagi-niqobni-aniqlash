# 📌 Face Mask Detection – Yuzdagi niqobni aniqlash  

## 📖 Loyiha haqida  
Ushbu loyiha **Convolutional Neural Networks (CNN)** asosida qurilgan **yuzdagi niqobni aniqlash** modeli bo‘lib, u real vaqtda odamning **niqob taqqan yoki taqmaganligini** aniqlaydi. Model **Keras va TensorFlow** kutubxonalaridan foydalangan holda tayyorlandi.

---

## 🚀 Xususiyatlari  
✅ **Real vaqt rejimida aniqlash** – Kamera orqali jonli tasvirlarni tahlil qilish  
✅ **Aniqlikni oshirish uchun optimallashtirilgan**  
✅ **3 ta sinfni aniqlash**:  
   - 🟢 **With Mask** – Niqob taqqan  
   - 🟡 **Mask Worn Incorrectly** – Niqob noto‘g‘ri taqqan  
   - 🔴 **Without Mask** – Niqobsiz  

---

## 🛠 Texnologiyalar va kutubxonalar  
🔹 Python  
🔹 TensorFlow / Keras  
🔹 OpenCV  
🔹 NumPy & Pandas  
🔹 Matplotlib & Seaborn  

---

## 📂 Loyihaning tuzilishi  
```bash
├── dataset/              # Annotatsiya qilingan ma'lumotlar to‘plami
│   ├── with_mask/        # Niqobli yuzlar
│   ├── without_mask/     # Niqobsiz yuzlar
│   ├── mask_weared_incorrect/  # Noto‘g‘ri taqqan niqoblar
│
├── model/                # Model arxitekturasi va og‘irliklar
│   ├── face_mask_model.h5
│
├── app.py                # Modelni ishga tushirish uchun Streamlit ilovasi
├── Web-kamera.ipynb      # Modelni tekshirish uchun Jupyter Notebook
├── README.md             # Loyihaning tavsifi
