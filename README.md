# Smart Parking Space Detection & Database Integration 

Sistem pemantauan dan deteksi ketersediaan slot parkir otomatis berbasis **Python**, **YOLO (Ultralytics)**, dan **OpenCV**, yang terintegrasi langsung dengan basis data (*database*) untuk melacak status slot parkir secara *real-time*.

---

##  Fitur Utama
* **Deteksi Kendaraan Pintar (YOLO)**: Menggunakan model *Deep Learning* YOLOv8 untuk mendeteksi keberadaan mobil secara dinamis dan akurat di area parkir.
* **Logika Interaksi Slot**: Menganalisis koordinat titik pusat kendaraan yang terdeteksi terhadap titik koordinat slot parkir yang telah ditentukan (*bounding box*).
* **Indikator Status Real-time**: Visualisasi warna interaktif langsung pada layar video (Hijau = Kosong, Merah = Terisi).
* **Sinkronisasi Database**: Menyimpan status ketersediaan slot parkir secara otomatis ke dalam *database* setiap kali terjadi perubahan status.
