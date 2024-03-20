# Klasifikasi dan Regresi dengan SVM
### Tugas 2 - Pembelajaran Mesin
- Zul akhyar
- 2008107010080
## Setting Up (Lokal)
Source code dapat dijalankan dengan meng-clone repository ini ke lokal, caranya pada terminal ketik `git clone` dan paste URL dari repository ini.

```sh
git clone https://github.com/zlkhyr/SVC-R.git
```

Setelah repository berhasil di clone, disarankan untuk membuat `virtual environment` / `venv` didalam project hasil cloning.

```sh
python -m venv /path/to/new/virtual/environment
```

Aktifkan virtual environment.

```sh
$ source <venv>/bin/activate
```

Install requirements.txt pada virtual environment.

```sh
pip install -r requirements.txt
```
Selanjutnya buka project menggunakan code editor `Visual Studio Code`, Pilih salah satu source code `SVC` atau `SVR` dan pada menu `change kernel` di pojok kanan atas pilih 
virtual environment yang telah dibuat sebelumnya, Klik `Run All` untuk menjalankan source code.

## Notebook
selain itu source code juga bisa di download dan dijalankan langsung menggunakan notebook seperti `Kaggle Notebook` `Google Colab` atau `Jupyter Notebook`, namun untuk jupyter notebook
masih tetap harus membuat `venv` dan menginstall requirements.txt
## Dataset 
### Klasifikasi
Dataset yang digunakan untuk klasifikasi adalah dataset yang berisi informasi terkait serangan jantung, digunakan untuk memprediksi apakah seseorang memiliki kemungkinan serangan jantung yang tinggi atau tidak 
### Regresi
Dataset yang digunakan untuk regresi berisikan informasi Nilai siswa termasuk waktu belajar & jumlah mata pelajaran, pada project ini digunakan untuk memprediksi pengaruh waktu belajar dan nilai siswa 
## Link Dataset
- [Dataset Klasifikasi](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset?resource=download)
- [Dataset Regresi](https://www.kaggle.com/datasets/yasserh/student-marks-dataset)
