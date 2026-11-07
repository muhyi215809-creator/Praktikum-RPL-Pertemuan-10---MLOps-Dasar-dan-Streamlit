# Praktikum RPL Pertemuan 10
## MLOps Dasar Sistem Prediksi Kelulusan Mahasiswa

### Deskripsi
Proyek ini merupakan hasil Praktikum Rekayasa Perangkat Lunak (RPL) Pertemuan 10. Aplikasi dibuat menggunakan Machine Learning dan Streamlit untuk memprediksi kelulusan mahasiswa berdasarkan IPK dan total SKS.

### Tujuan
- Melatih model Machine Learning menggunakan Decision Tree.
- Menyimpan model dalam format `.pkl`.
- Membuat aplikasi prediksi menggunakan Streamlit.
- Menghubungkan model Machine Learning dengan antarmuka pengguna.

### Teknologi yang Digunakan
- Python
- Scikit-learn
- NumPy
- Pandas
- Joblib
- Streamlit

### Struktur Proyek
```text
Pertemuan_10/
├── 1_latih_model.py
├── app.py
├── model_kelulusan.pkl
├── requirements.txt
└── README.md
```

### Cara Menjalankan

1. Instal library:
```bash
pip install -r requirements.txt
```

2. Latih model:
```bash
python 1_latih_model.py
```

3. Jalankan aplikasi:
```bash
streamlit run app.py
```

4. Buka alamat lokal yang muncul di terminal.

### Cara Penggunaan
1. Masukkan IPK mahasiswa.
2. Masukkan total SKS.
3. Klik tombol **Prediksi Kelulusan**.
4. Aplikasi akan menampilkan hasil prediksi.

### Metode Machine Learning
Algoritma yang digunakan adalah Decision Tree Classifier dengan data latih sederhana berupa IPK dan total SKS.
