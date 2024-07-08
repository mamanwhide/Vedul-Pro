# VedulPro
# Aplikasi Jual Beli Modul untuk Anak IT

Aplikasi ini adalah platform jual beli modul untuk mahasiswa dan profesional di bidang IT. Aplikasi ini dibangun menggunakan framework Flask dan menyediakan fitur-fitur seperti registrasi pengguna, upload modul, pembelian modul, dan banyak lagi.

## Instalasi

Ikuti langkah-langkah berikut untuk menginstal aplikasi ini di lingkungan lokal Anda:

1. **Clone repositori ini**:
    ```sh
    git clone https://github.com/mamanwhide/Vedul-Pro.git
    cd repo-name
    ```

2. **Buat virtual environment**:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Konfigurasi database**:
    - Edit file `config.py` untuk menyesuaikan konfigurasi database.
    - Jalankan perintah berikut untuk membuat database:
      ```sh
      flask db init
      flask db migrate -m "Initial migration."
      flask db upgrade
      ```

4. **Jalankan aplikasi**:
    ```sh
    flask run
    ```

Aplikasi akan berjalan di `http://127.0.0.1:5000/`.

## Struktur Proyek
Vedul-pro/
│
├── __pycache__/
│ ├── config.cpython-310.pyc
│ ├── config-cpython-311.pyc
├── app/
| ├──__pycache__/
│ ├── static
│ ├── templates
│ ├── init.py
│ ├── routes.py
│ ├── models.py
│ ├── forms.py
│ ├── templates/
│ └── static/
│
├── migrations/
│
├── venv/
│
├── pycache/
│
├── README.md
├── app.db
├── config.py
├── flaskapp.py
├── ft.txt
└── get-pip.py
