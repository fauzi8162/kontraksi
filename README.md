# 🤰 Bunda Helper - Contraction Timer
# https://fauzi8162.github.io/kontraksi/
**Bunda Helper** adalah aplikasi web sederhana dan responsif yang dirancang untuk membantu para ibu hamil (Bunda) dalam menghitung durasi serta jarak interval kontraksi menjelang persalinan. Aplikasi ini dilengkapi dengan algoritma rekomendasi otomatis untuk memberikan sinyal kapan waktu yang tepat untuk pergi ke rumah sakit atau menghubungi tenaga medis.

---

## ✨ Fitur Utama

* ⏱️ **Pencatat Kontraksi Real-time:** Memulai dan menghentikan penghitung waktu kontraksi hanya dengan satu tombol yang intuitif.
* 📊 **Analisis Interval Otomatis:** Menghitung jeda waktu (istirahat) antar-kontraksi secara otomatis berdasarkan data sebelumnya.
* 🚨 **Sistem Rekomendasi Pintar:** Menganalisis rata-rata durasi dan interval dari 5 kontraksi terakhir untuk memberikan status kondisi:
    * 🟢 **Tetap Tenang:** Kontraksi awal atau kontraksi palsu (Braxton Hicks).
    * 🟡 **Siap-siap:** Kontraksi mulai sering terjadi, disarankan menghubungi bidan/dokter.
    * 🔴 **Segera ke RS!:** Kontraksi sudah intens, teratur, dan menandakan waktu persalinan sudah dekat (Rekomendasi aturan 5-1-1).
* 💾 **Penyimpanan Lokal (LocalStorage):** Data kontraksi aman disimpan di browser dan tidak akan hilang meskipun halaman di-*refresh*.
* 🗑️ **Sistem Tab & Riwayat Hapus:** Memiliki tab khusus untuk melihat data aktif dan riwayat sesi pencatatan yang pernah dihapus agar layar tetap bersih namun data lama tidak langsung hilang.

---

## 🛠️ Teknologi yang Digunakan

Aplikasi ini dibangun menggunakan teknologi web dasar (*Single File Application*) tanpa memerlukan *library* atau *framework* tambahan:

* **HTML5** – Menangani struktur semantik halaman web.
* **CSS3 (Custom Properties & Flexbox)** – Desain antarmuka modern, bersih, ramah pengguna, dan responsif di perangkat *mobile*.
* **Vanilla JavaScript (ES6)** – Mengatur logika *timer*, manipulasi DOM, manajemen *state*, dan kalkulasi data.

---
---

## 📱 Panduan Penggunaan

1.  Ketika perut mulai terasa kencang/kontraksi, tekan tombol **"MULAI KONTRAKSI"**.
2.  Ketika rasa kencang hilang, klik tombol **"STOP (KONTRAKSI BERHENTI)"**. Data durasi dan jeda akan langsung tercatat di bawah.
3.  Lakukan minimal **3 sampai 5 kali** berturut-turut agar sistem rekomendasi dapat menganalisis pola kontraksi secara akurat.
4.  Gunakan tombol **"Hapus Semua & Pindahkan ke Riwayat"** jika ingin memulai sesi pencatatan yang baru. Data lama tetap bisa diintip di tab **"Riwayat Hapus"**.

---

## 📄 Lisensi

Proyek ini bersifat *open-source* di bawah lisensi [MIT License](LICENSE). Silakan gunakan, modifikasi, dan bagikan!

---

*Dibuat dengan 💝 untuk membantu perjalanan persalinan para Bunda.*
