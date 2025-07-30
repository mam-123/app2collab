#  Project Kolaborasi Android

Ini adalah projek sederhana untuk belajar kolaborasi menggunakan Git & Android Studio

## 👥 Tim
Imam Maulana Malik : Inisialisasi & Merge PR

Chyntia Fitri Ramadhani : Fitur TextView

Anzilul Nur Rohma : Fitur Button

## 📱 Fitur
Menampilkan TextView

Menampilkan Button yang bisa diklik


## 🔧 Teknologi
-Kotlin
Kotlin adalah bahasa pemrograman yang dikembangkan oleh JetBrains dan didukung oleh Google untuk pengembangan aplikasi Android.
-Android Studio
Android Studio adalah lingkungan pengembangan terpadu (IDE) resmi untuk pengembangan aplikasi Android yang dibuat dan didistribusikan oleh Google.
-Git & Github
Git adalah alat yang mengelola perubahan kode di komputer kita secara lokal, sedangkan GitHub adalah layanan online yang digunakan untuk menyimpan kode secara cloud.

## 📸 Penjelasan code penting
Handler(Looper.getMainLooper()).postDelayed({
    startActivity(Intent(this, MainActivity::class.java))
    finish()
}, 3000)

╰┈➤Fungsi: Menampilkan splash screen selama 3 detik, lalu berpindah ke MainActivity.

ProgressBar:

╰┈➤Fungsi: Tanda aplikasi sedang loading saat splash screen tampil. 

setContentView(R.layout.activity_main)

╰┈➤Fungsi: Menentukan layout yang digunakan yaitu activity_main.xml.

import android.content.Intent

import android.os.Bundle

import android.os.Handler

import android.os.Looper

import androidx.appcompat.app.AppCompatActivity

╰┈➤Digunakan agar kita bisa memakai class penting seperti Intent (pindah halaman), Handler (delay), dan AppCompatActivity (activity dasar Android).

Button

    android:id="@+id/btnTampilkan"
    
    android:text="Tampilkan"
    
╰┈➤Ketika ditekan, akan memproses input dan menampilkan hasilnya.

EditText etNama & etKelas

╰┈➤Fungsi: Tempat input nama dan kelas

TextView tvHasil

╰┈➤Fungsi: Menampilkan hasil input nama dan kelas.
## 📸 Screenshot
![WhatsApp Image 2025-07-30 at 18 58 05](https://github.com/user-attachments/assets/bc757972-80a3-4323-a451-8b45e3739a8e)
![WhatsApp Image 2025-07-30 at 18 58 06](https://github.com/user-attachments/assets/11b6e431-5442-4f34-8b7c-82890416d8e9)


