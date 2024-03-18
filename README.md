# Face_Recognition
## Cara Menjalankan Aplikasi:
1.	Menyiapkan Environment
Mengintal beberapa package Python yang diperlukan untuk aplikasi ini, seperti cv2, face_recognition, numpy, dan datetime. Instal package dapat menggunakan syntak pip, seperti berikut:
pip install face_recognition
2.	Mempersiapakan Dataset
Menyiapkan dataset gambar wajah yang akan digunakan oleh aplikasi. Gambar ini diletakkan di dalam folder yang imageData di dalam direktori tempat menyimpan kode aplikasi. Setiap gambar harus memiliki nama yang mengikuti format: Nama.NomorRegistrasi.jpg. Contohnya: `Suci.002.jpg`.
3.	Menjalankan Aplikasi
Membuka terminal atau command prompt, dengan mengarahkan ke direktori peyimpanana kode aplikasi.

## Cara Mengoperasikan Aplikasi:
1.	Aplikasi akan membuka kamera dan mulai mendeteksi wajah.
2.	Jika aplikasi berhasil mendeteksi wajah yang cocok dengan data yang telah disimpan, nama pengguna akan ditampilkan di atas wajah tersebut.
3.	Jika kecocokan ditemukan dan akurasi lebih dari 80%, data kehadiran akan dicatat dalam file CSV dengan nama Attendance.csv dan pada kode akan menghasilkan output “Pengguna Suci dengan nomor registrasi 002 berhasil ditambahkan”.
4.	Pada kamera, dapat menekan tombol 'A' untuk menambahkan pengguna baru ke dataset. Pengguna baru yang dimaksud merupakan pengguna yang data wajahnya belum ada di dalam folder imageData.
5.	Untuk keluar dari aplikasi kamera, cukup tekan tombol 'Q'.
