# NutriTrack
Aplikasi Pemantau Kalori & Nutrisi Harian Berbasis Android

## Deskripsi Project

NutriTrack merupakan aplikasi mobile berbasis Android yang dirancang untuk membantu pengguna memantau asupan kalori, nutrisi, dan hidrasi harian secara praktis.

Aplikasi ini menyediakan fitur kalkulasi BMR (untuk target kalori harian), pencarian makanan yang terintegrasi dengan Third-Party API (CalorieNinjas), serta fitur CRUD (Create, Read, Update, Delete) data makanan kustom yang dikelola oleh Admin melalui Cloud Database (Firebase Firestore). Data profil dan catatan harian pengguna disimpan secara lokal menggunakan DataStore (tanpa Room Database). Aplikasi ini dirancang untuk di-build dan di-deploy sebagai aplikasi Android siap pakai.

Aplikasi ini dikembangkan menggunakan Kotlin dan Jetpack Compose sebagai project akhir mata kuliah Pengembangan Aplikasi Mobile (PAM) 2026.

## Informasi Project

| Keterangan | Informasi |
| :--- | :--- |
| **Nama Project** | NutriTrack |
| **Tema** | Kesehatan |
| **Lingkup** | Pemantauan Kalori, Nutrisi, dan Hidrasi |
| **Platform** | Android |
| **Bahasa Pemrograman** | Kotlin |
| **UI Framework** | Jetpack Compose |
| **Arsitektur** | MVVM (Model-View-ViewModel) |
| **Database & Auth** | Firebase Firestore & Firebase Authentication (Cloud) |
| **Local Storage** | DataStore / SharedPreferences (Tanpa Room DB) |
| **Third-Party API** | CalorieNinjas API |

## Identitas Mahasiswa

| Keterangan | Informasi |
| :--- | :--- |
| **Nama** | Muhammad Randyano |
| **NIM** | 20240140271 |
| **Mata Kuliah** | Pengembangan Aplikasi Mobile (PAM) |

## Teknologi yang Direncanakan

*   **Kotlin** — Bahasa pemrograman aplikasi Android.
*   **Jetpack Compose** — Pengembangan antarmuka aplikasi (UI/UX) modern.
*   **MVVM & Navigation Compose** — Arsitektur dan navigasi aplikasi.
*   **Firebase (Firestore & Auth)** — Komunikasi, penyimpanan data cloud, dan autentikasi role (Admin/User).
*   **CalorieNinjas REST API** — Pengambilan data gizi makanan secara real-time.
*   **Retrofit & OkHttp** — Library untuk melakukan HTTP Request ke API.
*   **DataStore** — Penyimpanan preferensi lokal dan profil pengguna.
*   **Deployment Tools** — ProGuard/R8 & Keystore Signing untuk merilis APK.

Seluruh teknologi tersebut masih dalam tahap perencanaan dan akan diimplementasikan selama proses pengembangan.

## Fitur Utama yang Direncanakan

### Admin

*   Melakukan login ke dashboard khusus Admin.
*   Mengelola (Create, Read, Update, Delete) data Makanan Kustom yang tidak ada di API.
*   Menyimpan data Makanan Kustom ke Firebase Firestore agar bisa diakses oleh semua User.

### User

*   Melakukan registrasi dan login.
*   Mengisi profil (usia, berat, tinggi, gender) untuk kalkulasi BMR.
*   Melihat Dashboard Kalori & Hidrasi (Progress Bar).
*   Mencari makanan (menggabungkan hasil dari CalorieNinjas API dan Firebase Firestore).
*   Menambahkan makanan ke catatan harian.
*   Mencatat asupan air minum harian (+250ml).
*   Melihat riwayat aktivitas harian.

Seluruh fitur di atas merupakan rencana pengembangan dan belum diimplementasikan.

## Progress Pengembangan

### Penyusunan Software Requirements Specification (SRS)

**Status: In Progress**

Pada tahap ini dilakukan analisis kebutuhan dan penyusunan dokumen Software Requirements Specification (SRS) sebagai dasar perancangan dan pengembangan aplikasi NutriTrack.

Dokumen SRS dirancang mencakup:

1.  **Introduction** — Tujuan dan ruang lingkup aplikasi.
2.  **Overall Description** — Gambaran umum sistem, fitur, dan pengguna.
3.  **System Features** — Kebutuhan fungsional (Autentikasi, CRUD Admin, Tracking User).
4.  **External Interface Requirements** — Kebutuhan antarmuka, API, dan Firebase.
5.  **Other Nonfunctional Requirements** — Performa, keamanan, dan kualitas aplikasi.
6.  **Other Requirements** — Kebutuhan penyimpanan (tanpa Room) dan Deployment.
7.  **Appendix A: Glossary** — Istilah dalam dokumen.
8.  **Appendix B: Analysis Models** — Use Case Diagram, Flow Diagram, ERD, RAT, dan Arsitektur.
9.  **Appendix C: Issues List** — Catatan isu dan keputusan pengembangan.

### Ringkasan Progress

| Pertemuan | Kegiatan | Status |
| :--- | :--- | :--- |
| 9 | Analisis kebutuhan dan penyusunan SRS | In Progress |
| 10 | Perancangan sistem dan struktur data (Cloud & API) | Not Started |
| 11 | Perancangan UI/UX aplikasi | Not Started |
| 12 | Pengembangan integrasi REST API (CalorieNinjas) | Not Started |
| 13 | Implementasi autentikasi dan fitur utama (Admin & User) | Not Started |
| 14 | Integrasi aplikasi dengan Firebase Firestore | Not Started |
| 15 | Pengujian dan perbaikan aplikasi | Not Started |
| 16 | Finalisasi, Deployment (Build APK), dan presentasi | Not Started |

*Status progress akan diperbarui sesuai dengan perkembangan pengerjaan setiap pertemuan.*

## Dokumentasi

Dokumentasi project NutriTrack akan mencakup dokumen Software Requirements Specification (SRS), rancangan sistem, ERD, Use Case Diagram, Flow Diagram per fitur, desain antarmuka, serta dokumentasi implementasi dan pengujian aplikasi.

## Status Project

**Project Status: In Progress**

Pengembangan NutriTrack dilakukan secara bertahap sesuai dengan pedoman Project Akhir PAM 2026. Setiap perkembangan akan dicatat melalui commit dan pembaruan README pada repository GitHub.
