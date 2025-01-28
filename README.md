Info NISN
NISN adalah singkatan dari nomor induk siswa nasional. Nomor induk ini digunakan untuk mengidentifikasi bahwa para siswa sudah terdaftar secara nasional dalam kementerian pendidikan.


Nomor Induk Siswa Nasional (NISN) adalah kode pengenal siswa yang bersifat unik dan permanen yang diberikan oleh pemerintah kepada setiap siswa di Indonesia. 
NISN terdiri dari 10 digit angka yang dikelola oleh Kementerian Pendidikan dan Kebudayaan Republik Indonesia (Kemendikbud). 

NISN memiliki beberapa fungsi penting, di antaranya: 
Membedakan satu siswa dengan siswa lainnya di seluruh sekolah di Indonesia
Memudahkan identifikasi siswa di seluruh Indonesia
Sebagai syarat dalam pendaftaran peserta didik baru

Sebagai syarat mendapatkan berbagai program bantuan pendidikan, seperti Program Indonesia Pintar (PIP)
NISN biasanya tercantum dalam laporan pendidikan yang diterima siswa tiap semester. 
Jika lupa NISN, Anda dapat mengeceknya secara online dengan mengisi data-data berikut: Nama siswa, Tempat lahir, Tanggal lahir, Nama ibu, Kode captcha. 

Jika NISN tidak ditemukan, Anda dapat: 
Memastikan data yang dimasukkan sudah benar sesuai dengan data yang terdaftar di sekolah
Menghubungi operator Dapodik (Data Pokok Pendidikan) di sekolah
Menghubungi pusat layanan NISN di Kementerian melalui email atau kontak yang tertera di website


check from nik number(nomor ktp)
````
import http.client

conn = http.client.HTTPSConnection("nisn-checker.p.rapidapi.com")

payload = "nik=ktp-number"

headers = {
    'x-rapidapi-key': "key",
    'x-rapidapi-host': "nisn-checker.p.rapidapi.com",
    'Content-Type': "application/x-www-form-urlencoded"
}

conn.request("POST", "/nisn", payload, headers)

res = conn.getresponse()
data = res.read()

print(data.decode("utf-8"))
````

ckeck from nisn number
````
import http.client

conn = http.client.HTTPSConnection("nisn-checker.p.rapidapi.com")

payload = "nisn=nisn-number"

headers = {
    'x-rapidapi-key': "key",
    'x-rapidapi-host': "nisn-checker.p.rapidapi.com",
    'Content-Type': "application/x-www-form-urlencoded"
}

conn.request("POST", "/nisn", payload, headers)

res = conn.getresponse()
data = res.read()

print(data.decode("utf-8"))
````
