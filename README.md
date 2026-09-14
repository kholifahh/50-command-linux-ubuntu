# 50-command-linux-ubuntu
# 1. Menampilkan lokasi direktori saat ini
pwd
<img width="1280" height="800" alt="VirtualBox_kholifahubuntu_14_09_2026_21_54_07" src="https://github.com/user-attachments/assets/cea38dd3-e23d-4aa2-8153-fe71fbc8571d" />
# 2. Melihat isi direktori
ls
<img width="1280" height="800" alt="VirtualBox_kholifahubuntu_14_09_2026_21_57_01" src="https://github.com/user-attachments/assets/ac2d22ca-5d71-44a0-bede-adb977714925" />

# 3. Melihat isi direktori secara detail
ls -l
<img width="1280" height="800" alt="VirtualBox_kholifahubuntu_14_09_2026_21_58_58" src="https://github.com/user-attachments/assets/18db72b3-cca3-407f-acf7-3b0111aed970" />


# 4. Berpindah direktori
cd Documents
<img width="1280" height="800" alt="VirtualBox_kholifahubuntu_14_09_2026_22_01_01" src="https://github.com/user-attachments/assets/57f57bea-eeb1-4ec1-a1c3-a5760965d4dc" />


# 5. Kembali ke direktori sebelumnya
cd ..

# 6. Membuat direktori baru
mkdir tugas

# 7. Menghapus direktori kosong
rmdir tugas

# 8. Membuat file baru
touch data.txt

# 9. Menyalin file
cp data.txt backup.txt

# 10. Memindahkan atau mengganti nama file
mv data.txt dokumen.txt

# 11. Menghapus file
rm dokumen.txt

# 12. Menampilkan isi file
cat backup.txt

# 13. Membaca file per halaman
less backup.txt

# 14. Menampilkan 10 baris pertama
head backup.txt

# 15. Menampilkan 10 baris terakhir
tail backup.txt

# 16. Mengedit file dengan Nano
nano backup.txt

# 17. Membersihkan terminal
clear

# 18. Melihat riwayat command
history

# 19. Menampilkan teks
echo "Halo Linux Ubuntu"

# 20. Menampilkan username
whoami

# 21. Melihat pengguna yang sedang login
who

# 22. Menampilkan tanggal dan waktu
date

# 23. Menampilkan kalender
cal

# 24. Menampilkan informasi sistem
uname -a

# 25. Menampilkan nama komputer
hostname

# 26. Menampilkan lama sistem berjalan
uptime

# 27. Melihat penggunaan RAM
free -h

# 28. Melihat penggunaan disk
df -h

# 29. Melihat ukuran file dan direktori
du -h

# 30. Melihat proses yang sedang berjalan
top

# 31. Menampilkan daftar proses
ps aux

# 32. Menghentikan proses berdasarkan PID
kill 1234

# 33. Mengecek koneksi internet
ping google.com

# 34. Melihat informasi jaringan
ip addr

# 35. Melihat koneksi jaringan
ss -tuln

# 36. Mengunduh file
wget https://example.com/file.zip

# 37. Mengakses URL
curl https://example.com

# 38. Menjalankan command sebagai administrator
sudo ls

# 39. Memperbarui daftar paket
sudo apt update

# 40. Memperbarui paket yang terpasang
sudo apt upgrade

# 41. Menginstal aplikasi
sudo apt install git

# 42. Menghapus aplikasi
sudo apt remove git

# 43. Mencari paket
apt search python

# 44. Membuka manual command
man ls

# 45. Mencari teks dalam file
grep "Linux" backup.txt

# 46. Mencari file berdasarkan nama
find . -name "*.txt"

# 47. Mencari lokasi file
locate backup.txt

# 48. Mengubah permission file
chmod 755 script.sh

# 49. Mengubah pemilik file
sudo chown user backup.txt

# 50. Restart komputer
sudo reboot
