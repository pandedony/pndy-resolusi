# pndy-resolusi
Repository untuk menyimpan rencana pembelajaran pandedony
- git & github
1. Mengawasi Folder Menjadi Repository
	- $ git init
2. Untuk Cek
	- $ git status
3. Staging
	- $ git add <file>
	- $ git add . (add all)
	- $ git rm --cached <file> untuk remove
4. Commit
	- $ git commit 
		-m "Subject"
	- $ git config --global user.name "Pande Dony" (Masukan Username)
	- $ git config --global user.email "pandedonyy@gmail.com" (Masukan Email)
	- $ git commit -am "<coment>" (add data modified)
5. Log / History
	- $ git log
		-<berapa banyak>
	- $ git log -- <nama file>
	- $ git log --all --decorate --oneline --graph (menampilkan visualisasi branch)
6. Mengembalikan data hilang
	- $ git checkout <5 digit kode di awal> -- <nama file>
7. Branch
	- $ git branch (check branch)
	- $ git branch <nama branch> (untuk embuat branch baru)
	- $ git branch --merged (untuk mengetahui branch yang sudah di merge)
8. Alias
	- $ alias graph="git log --all --decorate --oneline --graph"
9. Ganti Branch
	- $ git checkout <nama branch>
10. Merge
	- $ git merbge <nama branch>
11. Delete Branch
	- $ git branch -d <nama branch>
	- $ git branch -D <nama branch> (delete without merge)
===========

LARAVEL
MANUAL
1. Pelajari Crud Laravel
	- https://www.youtube.com/watch?v=eRZFGSCkAnw&t=1452s part 1 (ada 4 part)
2. Belajar membuat registrasi, mempelajari bcrypt
3. Belajar membuat verifikasi email
4. belajar membuat lupa password yang dikirimkan melalui email
5. Belajar membuat login
