# **Prediksi BMI dengan Decision Tree Classifier**  

Proyek ini bertujuan untuk **memprediksi kategori BMI** seseorang berdasarkan **jenis kelamin, tinggi badan, dan berat badan** menggunakan algoritma **Decision Tree Classifier**.  

## 📌 **Dataset**  
Dataset berisi **489 data** setelah dilakukan pembersihan, dengan fitur:  
- **Jenis Kelamin** (*Laki-laki / Perempuan*)  
- **Tinggi Badan** (cm)  
- **Berat Badan** (kg)  
- **Label BMI** (*0-5, kategori berat badan berdasarkan indeks BMI*)  

## 🔍 **Tahapan Analisis**  
1. **Import Data** – Memuat dataset dan menampilkan informasi awal.  
2. **Data Cleaning** – Menghapus duplikat, menangani data kategorikal, dan melakukan standarisasi fitur.  
3. **Exploratory Data Analysis (EDA)** – Visualisasi distribusi data menggunakan **Seaborn** dan **Plotly**.  
4. **Data Preparation** – Encoding fitur kategorikal, standarisasi dengan **StandardScaler**, dan pembagian data latih/uji (**80:20**).  
5. **Modeling** – Melatih model **Decision Tree Classifier** dengan data latih.  
6. **Evaluasi Model** – Mengukur performa model dengan **accuracy, precision, recall, dan f1-score**.  
7. **Testing** – Menguji model dengan data baru untuk melihat hasil prediksi kategori BMI.  

## 📊 **Hasil Evaluasi Model**  
- **Akurasi Model**: **81.63%**  
- **Precision, Recall, F1-Score** menunjukkan performa yang cukup baik, terutama pada kategori dengan jumlah data lebih banyak.  

## 🛠 **Teknologi yang Digunakan**  
- **Python**  
- **Pandas, NumPy** (Manipulasi Data)  
- **Seaborn, Plotly, Matplotlib** (Visualisasi Data)  
- **Scikit-learn** (Model Machine Learning)  


## 📌 **Contoh Prediksi Data Baru**  
| Jenis Kelamin | Tinggi Badan | Berat Badan | Prediksi BMI |
|--------------|-------------|-------------|-------------|
| Perempuan | 168 cm | 200 kg | 5 (Obesitas Berat) |

## 📢 **Kesimpulan**  
- Model *Decision Tree Classifier* mampu memprediksi kategori BMI dengan akurasi **81.63%**.  
- Performa model dapat ditingkatkan dengan **tuning hyperparameter** atau menggunakan model lain seperti **Random Forest atau SVM**.  
