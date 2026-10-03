ZAKSS WORLD 5.4 - GitHub Actions Build

Cara build dari HP:
1. Buat repository GitHub baru.
2. Upload seluruh isi folder proyek ini ke repository.
3. Pastikan file .github/workflows/build-apk.yml ikut ter-upload.
4. Buka tab Actions.
5. Pilih "Build ZAKSS WORLD APK".
6. Tekan "Run workflow" jika tersedia.
7. Tunggu sampai job selesai.
8. Buka hasil workflow dan bagian Artifacts.
9. Download ZAKSS-WORLD-5.4-debug-apk.
10. Ekstrak ZIP artifact tersebut untuk mendapatkan app-debug.apk.

Workflow memakai Java 17 dan Gradle 8.7 di runner GitHub. Gradle wrapper dibuat otomatis saat build sehingga proyek ini tidak membutuhkan gradle-wrapper.jar yang disimpan di ZIP.
