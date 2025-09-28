# Tugas 4 Matematika Diskrit
**Nama: Siti Naia Hesti Rachmawati  
NPM: 24083010047  
Kelas: Matdis A**  

## 📖 Deskripsi
Repository ini berisi pengerjaan **Tugas 4 Matematika Diskrit** berupa simulasi pola makan menggunakan Python.  
Simulasi dilakukan untuk **500 sampel**, masing-masing selama **31 hari (2 kali makan per hari)**, dengan mempertimbangkan faktor:
- **Kenyang**
- **Rasa**
- **Sehat**
- **Bosanan**
- **Harga makanan**

Dataset makanan disimpan pada `makanan.csv`, kemudian dipakai untuk perhitungan skor dan simulasi anggaran bulanan.

## 📝 Tujuan Penugasan
1. Menemukan pola makan yang menghasilkan nilai kumulatif kesehatan (`resp_sehat`) positif.  
2. Mengidentifikasi titik dengan **sisa uang bulanan positif** dari pola sehat tersebut.  
3. Menentukan titik dengan **skor kumulatif terbesar** di mana nilai kesehatannya tetap positif.  
4. Menampilkan **jadwal makanan** (31 hari × 2 kali makan) sesuai pilihan simulasi terbaik.

## 📊 Hasil Utama
- ✅ Terdapat beberapa sampel dengan **skor kesehatan positif** dan sisa uang di atas 0.  
- ✅ Ditemukan sampel terbaik dengan **skor kumulatif maksimum** dan tetap sehat positif.  
- ✅ Jadwal lengkap makanan (pagi–malam) untuk 31 hari ditampilkan dari simulasi tersebut.  
- ✅ Visualisasi 3D menunjukkan hubungan antara **sisa budget**, **sample ID**, dan **skor kesehatan**.  

## ⚙️ Tools & Library
- Python 3  
- NumPy  
- Pandas  
- Matplotlib  

## 📂 Struktur Repository
.
├── Tugas_4_24083010047_Siti_Naia_Hesti_Rachmawati_Matdis_A.ipynb # Notebook utama
├── makanan.csv # Dataset makanan
├── hasil_simulasi.csv # Ringkasan hasil simulasi
├── resp_pilih_names.csv # Jadwal makanan (nama)
├── best_sample_full_schedule.csv # Jadwal makanan terbaik
└── resp_sehat_matrix.csv # Matriks kesehatan per bin sisa


## 🚀 Cara Menjalankan
1. Clone repository ini ke lokal atau buka langsung di Google Colab.  
2. Jalankan seluruh cell di notebook `.ipynb`.  
3. File hasil simulasi (CSV) akan otomatis dihasilkan di direktori kerja.  

---

✍️ *Repository ini dibuat untuk memenuhi tugas mata kuliah **Matematika Diskrit (Matdis A)**.*
