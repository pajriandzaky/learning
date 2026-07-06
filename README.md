# Learning github
## cara menambahkan folder ke github
cek github 

`git -v`

add username

`git config --global user.name "pajriandzaky"`

add email

`git config --blobal user.name "pajriandzaky@gmail.com"`

buka repositori yang mau di masukan 

`cd Documents/testing`

inisiasi dengan 

`git init`

untuk membuat repositori kosong yang ada di github

untuk cek status 

`git status`

menambahkan ke antrian sebelum di tambahkan ke github

`git add (nama file yang mau ditambahkan)`

simpan perubahan yang udah di buat ke history

`git commit -m "update repo"`

ubah nama cabang (branch) utama proyekmu menjadi main

`git branch -M main`

hubungkan repository lokal (di komputermu) dengan repository remote (di internet, seperti GitHub).

`git remote add origin <url_github>`

hubungkan proyek di komputermu ke halaman repository GitHub yang sudah kamu buat

`git remote add origin https://github.com/username/nama-repo.git`

adalah langkah terakhir untuk benar-benar mengupload (mengirim) semua file dan catatan komit dari komputermu ke repositori GitHub

`git push -u origin main`

*jika nanti ada pw itu bikin dlu dari token github nya bukan pake pw akun nya*
