
# Praktikum AR/VR - Pertemuan 1
## Scene Perkenalan Diri Menggunakan A-Frame

- Nama: Winda Wardani
- NIM: 2409020057
- Link DEMO: https://wndawardani25.github.io/arvr-prak-2409020057/

## Deskripsi Project

Project ini merupakan scene 3D sederhana untuk
memperkenalkan diri menggunakan WebXR dan A-Frame.
Scene memiliki kubus, bola, tabung, kerucut, dan torus,
serta lantai, langit, teks perkenalan, dan animasi.


## Refleksi

### 1. Mengapa posisi objek menggunakan nilai z negatif?

Pada A-Frame, kamera awal menghadap ke arah sumbu Z
negatif. Karena itu, objek yang diletakkan pada nilai
Z negatif berada di depan kamera dan dapat terlihat
oleh pengguna.

### 2. Mengapa WebXR hanya aktif pada HTTPS atau localhost?

WebXR memerlukan secure context untuk mengakses fitur
perangkat XR dengan aman. HTTPS menyediakan koneksi
yang aman, sedangkan localhost diizinkan untuk
pengembangan dan pengujian secara lokal.

### 3. Apa perbedaan WebXR Device API, three.js, dan A-Frame?

WebXR Device API menyediakan akses ke perangkat dan
sesi XR. Three.js membantu merender grafis 3D di web,
sedangkan A-Frame menyediakan elemen berbasis HTML
agar pembuatan scene 3D dan WebXR lebih mudah.
