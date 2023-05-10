# app-profile
Static Website for Dicoding Submission (Deploy app with App Engine)

# Instruksi
## Kriteria 1: Hosting Aplikasi Profile
Tentunya Anda sudah belajar bagaimana cara membuat Compute Engine instance, baik melalui Google Cloud console maupun gcloud CLI di Cloud Shell. Anda juga sudah paham bagaimana cara menginstal web server di sebuah VM. Nah, sekarang tugas Anda adalah meng-hosting aplikasi Profile buatan sendiri di Compute Engine. 

Silakan Anda bereksplorasi sedemikian rupa agar aplikasi yang Anda hosting menampilkan informasi mengenai profil Anda. Anda bisa menggunakan template atau merancangnya sendiri.

## Kriteria 2: Aplikasi Menampilkan Gambar
Aplikasi Profile yang Anda buat haruslah menampilkan gambar berupa foto profil yang disimpan di Cloud Storage. Anda juga boleh menambahkan gambar lain, misalnya banner ataupun background.

# Penilaian
Submission Anda akan dinilai oleh Reviewer dengan penilaian bintang berskala 1-5. Untuk mendapatkan nilai tinggi, Anda bisa menerapkan beberapa saran berikut:
- Alih-alih menggunakan Compute Engine, Anda meng-hosting aplikasi Profile di App Engine.
- Tampilan Aplikasi Profil rapi dan menarik, sebagai contoh:
  + Tidak menampilkan fitur yang tak relevan.
  + Alignment konten sedap dipandang.
  + Tampilan web layaknya halaman portofolio berkelas.

# ->
```
git clone https://github.com/klstak/app-profile.git
cd app-profile/
gcloud deploy app
gcloud browse app
