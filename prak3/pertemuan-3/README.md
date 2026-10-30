# Praktikum AVR - Pertemuan 3: Input dan Object Interaction (WebXR)

Folder ini berisi project WebXR interaktif yang mencakup fitur:
- Controller virtual dan garis sinar (`ray`).
- Interaksi *hover* (sorot lampu redup).
- Interaksi *select / grab* (menggenggam objek dengan *trigger*) dan *release* (melepas objek dengan posisi dunia terjaga menggunakan `attach`).
- Interaksi *squeeze* (mengubah warna objek dengan tombol *grip*).
- Manipulasi skala objek menggunakan *thumbstick* controller XR.
- Fallback interaksi klik mouse untuk pengujian mode desktop.

## Tabel Uji Fungsional

| No | Skenario uji | Hasil yang diharapkan | Hasil aktual | Status |
|----|--------------|------------------------|--------------|--------|
| 1 | Buka halaman di browser | Scene dan 3 objek tampil, tombol ENTER VR muncul | Sesuai harapan | Berhasil |
| 2 | Masuk sesi XR | Controller dan garis sinar tampil | Sesuai harapan | Berhasil |
| 3 | Arahkan sinar ke objek | Objek menyala redup (*hover*) | Sesuai harapan | Berhasil |
| 4 | Tekan dan tahan trigger pada objek | Objek ikut controller (*grab*) | Sesuai harapan | Berhasil |
| 5 | Lepas trigger | Objek tetap di posisi terakhir (*release*) | Sesuai harapan | Berhasil |
| 6 | Tekan grip pada objek | Warna objek berubah (*squeeze*) | Sesuai harapan | Berhasil |
| 7 | Geser thumbstick saat objek digenggam | Skala objek berubah, dibatasi 0,3 sampai 3 kali | Sesuai harapan | Berhasil |
| 8 | Klik objek dengan mouse (desktop) | Warna objek berubah | Sesuai harapan | Berhasil |
