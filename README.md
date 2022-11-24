# belajar-github

         git init => untuk inisialisasi projek
         git clone "link github projek "=> ambil projek dari github

         tanda U di file => undififie
         tanda M di file => Modified

         git add -A => menambah semua file yang ada di projek agar di pantau
         git commit -m "pesan" => menyimpan perubahan pencatatan data,
         sebelum melakukan commit pastikan file U atau M sudah di git add -A dahulu

         git status => melihat status

         git log => melihat riwayat commit
         git diff => melihat perubahan file

         .gitignore => pengecualian file

         branch = cabang
         git branch => melihat cabang
         git branch nama-cabang => membuat cabang
         git checkout nama-cabang => masuk ke cabang tertentu
         git merge nama-cabang => masuk ke cabang tertentu
         git branch -D nama-cabang => hapus cabang tertentu
         git branch -D nama-cabang cabang-lain => hapus cabang lebih dari 1

remote repositiry

         git remote add main link-github => connect di local dan repository github
         git push main master => upload file ke repository
         git pull main master => download file dari repository
