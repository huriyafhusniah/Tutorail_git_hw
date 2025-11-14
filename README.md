# Penjelasan Dasar Git

## Apa itu Git?
Git adalah version control system (VCS) yang digunakan untuk melacak perubahan pada file dan proyek.  
Git membantu tim untuk berkolaborasi dengan aman, mengelola versi file, dan menghindari konflik saat banyak orang mengerjakan proyek yang sama.

## Fungsi Git dalam Kolaborasi
1. Menyimpan riwayat perubahan file.
2. Memungkinkan kerja sama antar anggota tim melalui branch dan merge.
3. Memudahkan rollback ke versi sebelumnya jika terjadi kesalahan.

## Tiga Perintah Dasar Git

1. **git status**
   - Menampilkan status file di repository: file baru, file yang sudah diubah, atau file yang siap di-commit.
   - Contoh: `git status`

2. **git log**
   - Menampilkan riwayat commit dari repository, termasuk pesan, penulis, dan tanggal commit.
   - Contoh: `git log --oneline`

3. **git merge**
   - Digunakan untuk menggabungkan branch lain ke branch aktif saat ini.
   - Contoh: `git merge edit-readme`
