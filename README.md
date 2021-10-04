## INSTALASI GIT
Git adalah version control system yang digunakan para developer untuk mengembangkan software secara bersama-bersama. Fungsi utama git yaitu mengatur versi dari source code program anda dengan mengasih tanda baris dan code mana yang ditambah atau diganti.Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja. Git tersedia untuk berbagai sistem operasi. Precompiled binaries bisa diperoleh di halaman dowbload Git untuk 3 sistem operasi utama: Linux, Mac OS X, dan Windows. Git bisa menggunakan antarmuka grafis (GUI) maupun CLI (command line interface). Pada materi ini, kita akan banyak menggunakan antarmuka CLI melalui shell (Linux / Mac OS X) atau command prompt / PowerShell di Windows. 
berikut langkah-langkah menginstall Git:

1. Pertama kita download Git terlebih dahulu. 
    
    ![instal1](instalgit-1.png)

2. Setelah selesai download, buka file yang telah didownload lalu muncul lisensi dan klik next.  

    ![instal2](img/instalgit-2.png)

3. Pilih lokasi instalasi lalu klik next. 

    ![instal3](img/instalgit-3.png)

4. setelah itu pilih komponen lalu klik next. 

    ![instal4](img/instalgit-4.png)

5. selanjutnya mengisi shortcut untuk menu Start dan gunakan default Git lalu klik next. 

    ![instal5](img/instalgit-5.png)

6. Lalu pilih editor yang ingin digunakan dari Git. Pada pilihan ini, saya menggunakan visual studio code setelah itu klik next. 

    ![instal6](img/instalgit-6.png)
7. Pilih Git to name the initial branch pilihan pertama yaitu Let Git decide. 

    ![instal7](img/instalgit-7.png)

8. Lalu pilih path environment.

    ![instal8](img/instalgit-8.png)

9. Pilih openSSH untuk ssh.

    ![instal9](img/instalgit-9.png)

10. Pilih openSSL untuk HTTPS.

    ![instal10](img/instalgit-10.png)

11. Pilih opsi pertama untuk konversi akhir baris (CR-LF). 

    ![instal11](img/instalgit-11.png)

12. Selanjutnya pilih PuTTY untuk terminal yang digunakan untuk mengakses Git Bash.

    ![instal12](img/instalgit-12.png)

13. selanjut nya pilih Git Credential manager core. 

    ![instal13](img/instalgit-14.png)

14. Untuk opsi ekstra, pilih serta aktifkan enable file system caching. 

    ![instal14](img/instalgit-15.png)


15. Klik instal, setelah proses install selesai lalu klik finish. 

    ![instal15](img/instalgit-16.png)

16. Untuk mencoba atau melihat versi git dari command prompt, masuk ke command prompt, setelah itu eksekusi "git --version" untuk melihat apakah sudah terinstall atau belum. Jika sudah terinstall dengan benar, makan akan muncul hasil berikut:

    ![cekgit1](img/cekgit.png)

<br>

## KONFIGURASI GIT

Secara minimal, user harus memberitahu Git tentang username serta email yang digunakan setiap kali terjadi perubahan pada repo Git. Username serta email ini yang akan dimasukkan oleh Git ke catatan perubahan di repo. Di sistem operasi Windows, konfigurasi ini akan disimpan di C:\Document and Settings\NamaUser dengan nama file .gitconfig. Secara minimal, ada 2 hal yang perlu dikonfigurasi yaitu username dan email. <br>
langkah untuk konfigurasi Git sebagai berikut:
<br>

1. buka Git Bash di menu pencarian pada komputer/laptop.
     ![konfigurasi1](img/konfigurasi-1.png)
<br>

2. Setelah git bash terbuka ketik "git config --global user.name "Nama Anda di GitHub"",lalu ketik "git config --global user.email email@domain.tld"
    ![konfigurasi2](img/konfigurasi-2.png)
<br>

4. Untuk melihat konfigurasi yang sudah ada ketik"git config --list", lalu enter.
    ![konfigurasi3](img/konfigurasi-3.png)
<br>
Langkah ini cukup dilakukan sekali saja, kecuali jika ingin melakukan perubahan nama dan email.

<br>

## MENGELOLA REPO SENDIRI
<br>
 MENGELOLA REPO SENDIRI DI ACCOUNT SENDIRI :
 <br>
 1. Buka github.com lalu jika tidak mempunyai akun harus membuat terlebih dahulu, setelah itu login.
 <br>

 2. Klik tanda + pada bagian atas, setelah itu pilih New repository.
    ![kelola1](img/kelola-1.png)
 <br>

 3. setelah itu isikan nama, deskripsi, type repo, serta lisensi. Jika sudah klik Create Repository.
    ![kelola2](img/kelola-2.png)
 <br>

## CLONE REPO
 Proses clone adalah proses untuk menduplikasikan remote repo di GitHub ke komputer lokal. Untuk melakukan proses clone ikuti langkah-langkah berikut:
 <br>

 1. Buka Github dan login terlebih dahulu.
 <br>

 2. lalu pilih lokasi penyimpanan/folder untuk penyimpanan clone repo yang akan disimpan.
 <br>

 3. setelah itu klik kanan pada folder yang mau disimpan, setelah itu pilih Git bash here.
    ![clone1](img/clone-1.png)
 <br>

 4. Lalu buka kembali Github dan pilih repo yang akan disimpan.<br>

 5. Kemudian klik tombol "Code" dan copy paste link https nya.
    ![clone2](img/clone-2.png)
 <br>

 6. buka kembali Git bash (cmd), lalu ketik "git clone https://github.com/wiratama43/01-git-github.git" setelah itu enter dan seperti ini hasil nya:
    ![clone3](img/clone-3.png)
</ul>

## MENGELOLA REPO

MENGUBAH ISI MELALUI VISUAL STUDIO CODE :
1. 
 