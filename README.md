# Data Wrangling Proyek Analisis Data

Proyek ini bertujuan untuk mempraktikkan proses **Data Wrangling** menggunakan dataset **DicodingCollection**, yang terdiri dari empat tabel: `customers`, `orders`, `products`, dan `sales`. Dataset ini diambil dari [Dicoding Dataset](https://github.com/dicodingacademy/dicoding_dataset/tree/main/DicodingCollection).

## Tujuan Proyek

1. Mengumpulkan dan menggabungkan data dari berbagai tabel.
2. Menilai kualitas data (missing values, duplikasi, format tidak konsisten).
3. Membersihkan data agar siap dianalisis.

## Alur Kerja

1. **Setup Virtual Environment**:
    - Buat environment menggunakan `pipenv`.
    - Instal library: `numpy`, `pandas`, `scipy`, `matplotlib`, `seaborn`, `jupyter`.

2. **Tahapan Wrangling**:
    - **Gathering Data**: Mengimpor dan menggabungkan dataset.
    - **Assessing Data**: Mengecek missing values, duplikasi, dan ketidakkonsistenan.
    - **Cleaning Data**: Memperbaiki masalah untuk menghasilkan dataset bersih.

## Cara Penggunaan

1. Buat folder proyek:
    ```bash
    mkdir proyek_analisis_data
    cd proyek_analisis_data
    ```

2. Setup virtual environment:
    ```bash
    pipenv install
    pipenv shell
    pip install numpy pandas scipy matplotlib seaborn jupyter
    ```

3. Jalankan Jupyter Notebook:
    ```bash
    jupyter-notebook .
    ```

4. Tambahkan file baru bernama `notebook.ipynb` dan lakukan proses data wrangling di file tersebut.

## Sumber Dataset

Dataset yang digunakan dalam proyek ini dapat diakses melalui repository berikut:  
[Dicoding Dataset - DicodingCollection](https://github.com/dicodingacademy/dicoding_dataset/tree/main/DicodingCollection).
