# PROJECT UTS ALGORITMA & STRUKTUR DATA

## 1. Identitas Mahasiswa
- **Nama** : Shafa Fadilah Wibisono
- **NPM** : G1F026001
- **Kelas** : Sistem Informasi A

## 2. Judul Project
- Implementasi Struktur Data Array dan Linked List pada Sistem Katalog Produk Kecantikan

## 3. Deskripsi Singkat Project
Program ini dikembangkan untuk memenuhi Ujian Tengah Semester (UTS) mata kuliah Algoritma dan Struktur Data. Aplikasi berbasis teks ini dirancang untuk mengelola katalog produk kecantikan (Makeup, Skincare, Bodycare, Haircare) dengan menerapkan dua struktur data utama, yaitu Array/List Python dan Linked List manual menggunakan Node.

## 4. Bahasa Pemrograman
- Python

## 5. Struktur Direktori dan Berkas
```text
project_uts/
├── main.py              -> Berisi logika antarmuka menu utama dan alur program
├── array_data.py        -> Modul pengelolaan data menggunakan Array/List
├── linked_list.py       -> Modul implementasi Linked List
├── node.py              -> Modul definisi struktur class Node
├── data/
│   └── data.csv         -> Berkas penyimpanan data eksternal/arsip pendukung
└── README.md            -> Berkas informasi dan petunjuk penggunaan
```

## 6. Cara Menjalankan Program
1. Buka aplikasi VS Code dan buka folder `project_uts`.
2. Buka terminal baru (**Terminal > New Terminal**).
3. Ketik perintah berikut:
   ```bash
   python main.py
   ```

## 7. Penjelasan Singkat Struktur Data
- **Array/List**: Struktur data linier dengan indeks berurutan. Unggul dalam akses data langsung (*random access*).
- **Linked List**: Struktur data dinamis berbasis Node yang saling terhubung melalui referensi (*pointer*), sangat efisien untuk operasi penyisipan dan penghapusan data.