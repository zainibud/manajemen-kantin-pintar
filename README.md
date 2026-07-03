Team Manifesto
Proyek: Aplikasi Mobile Kantin Pintar Kampus
Deliverable B Komunikasi Tertulis & Resolusi Konflik
1. Latar Belakang & Tujuan Dokumen
Tim Scrum kami mengambil alih proyek Aplikasi Mobile Kantin Pintar Kampus setelah tim
sebelumnya bubar akibat konflik internal, dengan sisa waktu 2 minggu menuju deployment.
Kondisi yang kami warisi:
Masalah Tim Lama Akar Penyebab
Backend & frontend saling
menyalahkan
Format data JSON berubah tanpa
komunikasi/dokumentasi
Progres stagnan di 50% Tidak ada pembagian tugas & alur kerja yang jelas
Product Owner marah-marah Tidak ada transparansi progres & saluran komunikasi
yang sehat
Kode berantakan, tanpa
dokumentasi Tidak ada SOP Code Review dan standar kerja
Dokumen ini adalah kebijakan tim (Team Manifesto) yang kami sepakati bersama agar pola
konflik di atas tidak terulang dalam 2 minggu ke depan. Setiap aturan di bawah ini secara
langsung menjawab satu masalah spesifik yang menyebabkan proyek lama gagal.
1. Tim Scrum
Role Tanggung Jawab
Product Owner Menentukan kebutuhan sistem dan prioritas fitur
Scrum Master Memastikan proses Scrum berjalan dengan baik serta menghilangkan
hambatan tim
Backend Developer Mengembangkan API dan database
Frontend Developer Mengembangkan antarmuka aplikasi mobile
UI/UX Designer Mendesain tampilan dan pengalaman pengguna
Quality Assurance
(QA) Melakukan pengujian dan memastikan kualitas aplikasi
Visi Tim
Kami berkomitmen menyelesaikan proyek Aplikasi Mobile Kantin Pintar Kampus secara
profesional dengan mengutamakan komunikasi yang terbuka, kerja sama tim, kualitas
perangkat lunak, serta kepuasan Product Owner — sekaligus memulihkan kepercayaan yang
sempat hilang akibat kegagalan tim sebelumnya.
Nilai-Nilai Tim
• Komunikasi Terbuka
• Saling Menghargai
• Bertanggung Jawab
• Transparansi
• Kolaborasi
• Disiplin
• Continuous Improvement
2. Aturan Kerja Tim
Daily Scrum
Dilaksanakan setiap hari, maksimal 15 menit.
Agenda:
• Apa yang sudah dikerjakan kemarin?
• Apa yang akan dikerjakan hari ini?
• Hambatan apa yang sedang dihadapi?.
Sprint Planning
Dilaksanakan di awal sprint untuk menentukan backlog sprint, target sprint, dan membagi
tugas ke setiap anggota secara adil.
Sprint Review
Dilaksanakan setelah sprint selesai: mendemonstrasikan hasil kerja ke Product Owner,
menerima masukan, menentukan perbaikan.
Sprint Retrospective
Dilaksanakan setelah Sprint Review, membahas: hal yang berjalan baik, hal yang perlu
diperbaiki, dan rencana peningkatan sprint berikutnya.
3. SOP Code Review
Tujuan
Meningkatkan kualitas kode, menemukan bug lebih awal, dan membangun budaya belajar
bersama — bukan ajang saling menyalahkan seperti yang terjadi di tim sebelumnya.
Aturan Code Review
1. Review fokus pada kode, bukan orangnya.
2. Gunakan bahasa yang sopan dan profesional.
3. Sertakan alasan teknis ketika memberikan masukan.
4. Hindari komentar yang menjatuhkan.
5. Berikan solusi apabila menemukan masalah, bukan sekadar kritik.
6. Pull Request harus disetujui minimal oleh satu reviewer sebelum di-merge.
Contoh Komentar yang Dilarang:
• "Coding kamu jelek."
• "Ini salah semua."
• "Kamu bikin error terus."
• "Saya tidak mengerti kenapa kamu membuat kode seperti ini."
• "Perbaiki sendiri."
Contoh Komentar yang Dianjurkan:
• "Bagian ini mungkin bisa dibuat lebih efisien menggunakan fungsi helper."
• "Apakah validasi input dapat ditambahkan untuk mengurangi kemungkinan error?"
• "Saya menyarankan penggunaan nama variabel yang lebih deskriptif agar mudah
dipahami."
• "Logika ini sudah berjalan dengan baik, tetapi mungkin dapat dioptimalkan."
• "Terima kasih atas implementasinya. Saya memiliki beberapa saran kecil untuk
meningkatkan kualitas kode."
4. Git Workflow
Seluruh pengembangan mengikuti Git Flow sederhana.
Branch:
main
develop
feature/login
feature/menu
feature/payment
bugfix/*
hotfix/*
Aturan:
• Tidak diperbolehkan commit langsung ke branch main.
• Seluruh perubahan dilakukan melalui Pull Request.
• Pull Request wajib melalui Code Review (lihat Bagian 3).
Standar Commit (Conventional Commits)
Feat : menambahkan fitur login
Fix : memperbaiki bug autentikasi
Docs : memperbarui dokumentasi API
Style : merapikan tampilan UI
Refactor : menyederhanakan fungsi checkout
Test : menambahkan unit testing
Chore : memperbarui dependency
5. Protokol Komunikasi
Media Komunikasi
• WhatsApp Group
• Discord / Microsoft Teams
• GitHub Issues
• GitHub Discussion
Jam Kerja : Senin – Jumat, 08.00 – 17.00 WIB
Jam Koordinasi :
19.00 – 21.00 WIB
Di Atas Jam 21.00 WIB
Tidak diperbolehkan mengirim pesan koordinasi, kecuali:
• Server mengalami down
• Bug Critical
• Deployment gagal
• Permintaan mendesak dari Product Owner
Response Time
Prioritas Maksimal Respon
Tinggi 15 menit
Sedang 1 jam
Rendah Maksimal hari kerja berikutnya
6. Penyelesaian Konflik
Apabila terjadi konflik antar-anggota:
1. Diskusi secara langsung terlebih dahulu.
2. Apabila belum selesai, melibatkan Scrum Master sebagai mediator.
3. Jika masih terjadi perbedaan pendapat, Product Owner menjadi pengambil keputusan
akhir.
4. Semua keputusan dicatat pada GitHub Issues atau Meeting Notes agar tidak terulang
jadi konflik yang sama.
7. Dokumentasi API Solusi untuk Masalah "Format JSON Berubah-ubah"
Seluruh endpoint API wajib didokumentasikan menggunakan Swagger/OpenAPI, mencakup:
• Endpoint
• Method
• Parameter
• Request Body
• Response JSON
• HTTP Status Code
Aturan kunci: Perubahan format JSON tidak boleh dilakukan tanpa persetujuan seluruh
anggota yang terkait (backend & frontend).
8. Definition of Done (DoD)
Dinyatakan selesai apabila:
• Kode berhasil dikompilasi
• Tidak terdapat error
• Unit Testing berhasil
• Code Review disetujui
• Dokumentasi diperbarui
• Pull Request telah di-merge
• Product Owner menerima hasil implementasi
9. Manajemen Risiko
Risiko
a) Perubahan API mendadak
b) Konflik anggota
c) Keterlambatan tugas (sisa waktu 2 minggu)
d) Bug saat deployment
e) Dokumentasi tidak diperbarui
Mitigasi
a) Freeze API sebelum Sprint dimulai
b) Mediasi oleh Scrum Master
c) Pair Programming dan redistribusi tugas
d) Melakukan staging dan regression testing
e) Dokumentasi menjadi bagian dari Definition of Done
10. Komitmen Tim
Kami berkomitmen untuk:
• Menjaga komunikasi yang profesional.
• Menghormati pendapat setiap anggota.
• Mengutamakan kualitas perangkat lunak.
• Menyelesaikan proyek sesuai target sprint dalam sisa waktu 2 minggu.
• Memberikan hasil terbaik kepada Product Owner dan memulihkan kepercayaannya
