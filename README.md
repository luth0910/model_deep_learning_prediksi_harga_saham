# 📈 Stock Price Prediction using LSTM  
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)  
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-LSTM-green)  

🚀 **Prediksi Harga Saham PT Astra International Tbk** menggunakan **Long Short-Term Memory (LSTM)**, salah satu teknik Deep Learning untuk analisis deret waktu. Model ini dikembangkan sebagai bagian dari **proyek penelitian ilmiah di Universitas Gunadarma**.  

---

## 📊 **Tentang Proyek**
Proyek ini merupakan **penelitian ilmiah** yang bertujuan untuk **menganalisis dan memprediksi harga saham PT Astra International Tbk (ASII)** menggunakan metode **Long Short-Term Memory (LSTM)**.  

LSTM adalah model **Recurrent Neural Network (RNN)** yang mampu menangkap pola jangka panjang dalam data sekuensial, seperti **harga saham**, sehingga cocok untuk analisis pasar keuangan.

### 🔥 **Fitur Utama**
✅ **Preprocessing Data**: Normalisasi, penghapusan noise, dan pemisahan data.  
✅ **Model LSTM**: Arsitektur yang dirancang untuk menangkap pola dalam data saham.  
✅ **Evaluasi Model**: Metrik RMSE dan Visualisasi prediksi vs. harga aktual.  
✅ **Prediksi Masa Depan**: Menghasilkan prediksi harga saham berdasarkan data historis.  

---

## 🎓 **Universitas & Peneliti**
📌 **Universitas Gunadarma**  
📌 **Proyek Penelitian Ilmiah dalam bidang Deep Learning dan Pasar Keuangan**  
📌 **Peneliti**: [Muhammad Ruhunul Luthfi]  

---

## 📁 **Dataset**
📌 Data harga saham PT Astra International Tbk diambil dari **Yahoo Finance** atau sumber lain yang valid.  
📌 Fitur utama yang digunakan:  
- **Tanggal**
- **Harga Penutupan (Close)**
- **Volume Perdagangan**  

💡 Jika ingin menggunakan dataset berbeda, pastikan formatnya sesuai dengan yang digunakan dalam proyek ini.

---

## 🏗 **Arsitektur Model**
Model LSTM yang digunakan memiliki **3 lapisan utama**:
1. **LSTM Layer** - Menangkap pola dalam data saham.
2. **Dropout Layer** - Mencegah overfitting.
3. **Dense Layer** - Menghasilkan prediksi harga saham.

---

## ⚙️ **Instalasi & Penggunaan**
### 1️⃣ **Clone Repository**
```bash
git clone https://github.com/username/stock-price-prediction-lstm.git
cd stock-price-prediction-lstm
