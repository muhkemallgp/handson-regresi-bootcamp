# Hands-on Lab: Regression untuk Analitik Perbankan

Bootcamp Data Analytics, Artificial Intelligence, dan Big Data
Officer Development Program - Data Analytics · Pusilkom UI

---

## Buka Langsung di Google Colab

Klik salah satu tombol di bawah. Tidak perlu memasang apa pun di laptop Anda, dan tidak perlu mengunggah berkas data. Semua dataset sudah tertanam di dalam notebook.

| Notebook | Untuk siapa | Buka |
|----------|-------------|------|
| **01 · Lab Regresi** | Peserta | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/muhkemallgp/handson-regresi-bootcamp/blob/main/notebooks/01_Lab_Regresi.ipynb) |
| **02 · Lab Regresi (sudah dijalankan)** | Rujukan, semua keluaran sudah terisi | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/muhkemallgp/handson-regresi-bootcamp/blob/main/notebooks/02_Lab_Regresi_REFERENSI.ipynb) |
| **03 · Starter Kompetisi Kaggle** | Peserta kompetisi | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/muhkemallgp/handson-regresi-bootcamp/blob/main/notebooks/03_Starter_Kaggle.ipynb) |

> Setelah Colab terbuka, klik **File** lalu **Save a copy in Drive** supaya pekerjaan Anda tersimpan. Tanpa itu, perubahan Anda hilang saat tab ditutup.

---

## Isi Materi

Lab ini menutup tujuh topik secara berurutan, memakai satu kasus nyata perbankan yaitu penentuan limit kartu kredit nasabah.

| Bagian | Topik |
|--------|-------|
| 1 | Intro to Regression |
| 2 | Simple Linear Regression, termasuk menurunkan OLS secara manual |
| 3 | Multiple Linear Regression dan normal equation |
| 4 | OLS vs SGD |
| 5 | Evaluating and Interpreting Regression Result |
| 6 | Multicollinearity |
| 7 | Overfitting |
| 8 | Polynomial Regression |

Durasi sesi 2 jam. Di sepanjang notebook ada empat kotak **Giliran Anda**, yaitu tugas singkat dua menit untuk mengubah satu nilai lalu mengamati akibatnya.

---

## Kompetisi Kaggle

Setelah sesi hands-on, ada kompetisi memprediksi **biaya operasional cabang**. Notebook 03 membawa Anda sampai submission pertama yang valid dalam sekitar sepuluh menit.

Notebook 03 mengenali sendiri tempat ia dijalankan. Di Kaggle Notebook, data diambil dari folder input kompetisi. Di Colab atau laptop, data ditulis dari salinan bawaan notebook.

Satu petunjuk yang sengaja dibocorkan. Melempar Random Forest ke data mentah **tidak** memenangkan kompetisi ini. Yang menang adalah yang memahami bentuk hubungan di dalam datanya, dan semua bekalnya sudah ada di Bagian 6 sampai 8.

---

## Menjalankan di Laptop Sendiri

Kalau memilih tidak memakai Colab:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy statsmodels jupyter
jupyter notebook
```

Notebook tetap menulis berkas datanya sendiri, jadi folder `data/` sifatnya hanya cadangan.

---

## Catatan Data

Seluruh dataset dibangkitkan secara sintetis khusus untuk pelatihan ini. Tidak ada data nasabah, cabang, maupun keuangan sebenarnya di dalamnya.
