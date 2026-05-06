
# Praktikum Git & GitHub - PPW

Repositori ini dibuat untuk memenuhi tugas praktikum mata kuliah Pengembangan Aplikasi Web. Project ini fokus pada implementasi kontrol versi menggunakan Git dan manajemen repositori di GitHub.

## Deskripsi Project
Tugas PPW pertemuan ke 10 mengenai git dan github 

## Langkah Langkah 1
1. Buat sebuah repository pada github beri nama praktikum-git-NIU
![Proses membuat repository](gambar%201.png)

2. melakukan clone dengan url yang muncul pada repository dan menyalinnya ke terminal dengan git clone sehingga dan klik enter
![Proses cloning](gambar2.png)

3. menambahkan file baru yang namanya .gitignore lalu didalamnya adalah .DS_Store
*.log
node_modules/ lalu melakukan commit dengan perintah git commit-m "chore: add .gitignore" yang artinya kita menambahkan commit dengan komen chore: add .gitignore (seperti yang saya tampilkan di baris pertama log commit yang saya panggil dengan git log --oneline)
![Proses menambahkan file .gitignore dan menambahkan commit](gambar3.png)

4. Hasil git log:
![Log git](gitlog.png)

## Langkah langkah 2
1. membuat 3 buah branch yaitu feature/navbar, feature/footer, dan hotfix/typo dengan perintah git branch feature/footer untuk membuatnya atau langsung git checkout feature/footer untuk langsung ke branchnya 
![membuat branch feature footer](gambar4.png)
![membuat branch feature navbar](gambar5.png)
![membuat branch hotfix typo](gambar6.png)

2. pada gambar diatas setiap branch sudah di push, menuju ke tab github dan PR setiap branch dan beri judul yang jelas sampai menjadi seperti pada gambar
![tampilan setelah melakukan PR](gambar7.png)

3. jadi satu dengan nomor 2

4. Pasang branch protection commit rule di github
![membuat branch protection rule](gambar8.png)

## Langkah langkah 3
1. membuat 2 branch, yaitu experiment/color-A dan experiment/color-B. Dimana kedua branch, ubah baris CSS yang sama yaitu warna background yaitu pink dan soft blue
![membuat branch background pertama](gambar9.png)
![membuat branch background kedua](gambar10.png)
 maka akan menimbulkan konflik karena yang dirubah kedua branch adalah 1 baris yang sama dan perubahan beda maka merge kedua nya dengan perintah git push -u origin sehingga muncul tampilan seperti berikut
![tampilan conflict](gambar11.png)

2. lakukan merge dengan perintah git merge serta fix conflictnya secara manual di vscode
![fix conflict](gambar12.png)

3. membuat branch baru bernama feature/dark-mode yang berisi 3 commit di sana. Kemudian masuk ke interactive rebase untuk menggabungkan (squash) 3 commit menjadi 1 commit dengan pesan yang baik.
![fix conflict](gambar13.png)
![fix conflict](gambar14.png)
![fix conflict](gambar15.png)
