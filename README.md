# Tutorial GIT

- Syarat:
  - Install [Git](https://git-scm.com/downloads/)
  - Buat Akun [Github](https://github.com/)
  - Buat Repository Public Pada Github, Contoh: `tutorial-git`
  - Buat Folder Project Pada Device Local, Contoh: `github`
  - Masuk Ke Folder Project (`github`)
  - Inisialisasi Repository Melalui Perintah `git init`
  - Jalankan Perintah `git remote add origin <url>`
  - URL Mengarah Ke Repository Public Yang Dibuat Sebelumnya (`tutorial-git`).
  - Ketikan perintah `git pull origin main` Untuk Mengunduh Perubahan File Dari Repository Cloud (`tutorial-git`) Ke Repository Local (`github`).
  - Tambahkan 1 File Misalkan `index.php` Yang Berisi:
    ```
    <?php
    echo "Helo Git & Github";
    ?>
  - Ketikan Perintah `git add .` Untuk Menandai Perubahan File Yang Akan Disimpan Dalam Repository Git.
  - Ketikan Perintah `git commit -m "Menambah file readme."` Untuk Menyimpan Perubahan File Pada Proses Sebelumnya (`git add .`) Pada Repository Local Git.
  - Ketikan Perintah `git push origin main` Untuk Mengirim Atau Menyimpan Perubahan Pada Repository Remote.

- ***Catatan:***
  - **Repository Local** Merupakan Repository Yang Disimpan Dalam Device Local.
  - **Repository Public** Atau Remote Merupakan Repository Cloud, Seperti Github.