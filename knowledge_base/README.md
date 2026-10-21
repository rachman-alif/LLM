# Knowledge Base

Folder ini sengaja **kosong di repo** (`*.pdf` ada di `.gitignore`).

## Sumber yang dipakai pada eksperimen

| Dokumen | Jenis | Kategori | Boleh di-commit? |
|---|---|---|---|
| `Troubleshooting.pdf` | Buku jaringan | Network | ❌ cek hak cipta |
| `Buku-Troubleshooting-Komputer-Full.pdf` | Buku komputer | Hardware/Software | ❌ cek hak cipta |
| `13 Hosting Website.pdf` | Slide kuliah (berbasis gambar, di-OCR) | Hosting | ❌ milik dosen/penulis slide |
| `Dokumen Knowledge Base IT Service Desk.pdf` | SOP internal | SOP Internal | ✅ jika Anda penulisnya |
| `Knowledge_Base_IT_Service_Desk_RAG.pdf` | SOP internal | SOP Internal | ✅ jika Anda penulisnya |

## Cara memakai
1. Siapkan PDF sendiri (SOP, FAQ, panduan troubleshooting).
2. Daftarkan nama file dan kategorinya di dict `SOURCES` pada sel konfigurasi notebook (`kind`: `book` untuk teks digital, `slides` untuk slide berbasis gambar yang perlu OCR).
3. Unggah lewat sel *Upload Dokumen PDF*.

## Disarankan untuk portofolio
Buat 15–25 dokumen SOP sintetis milik sendiri (reset password, VPN, printer, Wi-Fi, email, akses aplikasi) dan simpan di `data/knowledge_base_sample/` agar siapa pun bisa mereproduksi demo tanpa masalah lisensi. Hapus `data/knowledge_base_sample/*.pdf` dari `.gitignore` jika ingin meng-commit-nya.
