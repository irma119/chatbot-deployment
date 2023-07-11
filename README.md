# Chatbot Deployment Unichat

referensi [this](https://github.com/python-engineer/pytorch-chatbot) tutorial menggunakan Flask dan JavaScript.

Sebelumnya silahkan anda dowload package berikut:
pip install flask
pip install json

## Setup di CMD:
Silahkan buka cmd di laptop kalian dan activkan environment yang biasa di pakai untuk program misal "Python 3.10.9-bit"

Ikuti perintah berikut untuk mengaktifkan environment yang anda pakai
"CATATAN SILAHKAN SESUAIKAN LOCAL DISK FOLDER YANG ANDA SIMPAN"
disini saya menggunakan local disk F: dengan environment base miniconda
```
$ F:
$ cd F:\Kampus Merdeka AI\Final Project\chatbot-deployment-main
$ conda activate base 
```
Berikut jika aktivasi environment berhasil
(base) F:\Kampus Merdeka AI\Final Project\chatbot-deployment-main>

Selanjutnya Install package flask
```
$ (base)pip install Flask torch torchvision nltk
```
Setelah selesai, Install nltk package
```
$ (base) python
>>> import nltk
>>> nltk.download('punkt')
>>> ctrl+z/quit
```
Jika berhasil silahkan ctrl+z untuk keluar dari program tersebut
Running train.py untuk melihat nilai akurasi model
```
$ (base) python train.py
```
pada proses ini data.pth akan otomatis tersimpan untuk mengetes chatbot bisa digunakan 
silahkan running chat.py
```
$ (base) python chat.py
```
Setelah selesai silahkan buka folder sudah di download di visual code  

![Capture](https://github.com/irma119/chatbot-deployment-unichat/assets/110200862/a446405c-62dd-4e94-b6f9-20ec34bb23f8) ini hanya sebagai contoh

silahkan running app.py dan ketikan flask running di terminal 
![Capture-1](https://github.com/irma119/chatbot-deployment-unichat/assets/110200862/ec0b0464-4fc5-425e-97fd-94a01e8ca593)
silahkan klik link tersebut untuk melihat tampilan aplikasi 

Note: "DIHARAPKAN SEMUA FILE DIBUAT SATU FOLDER JIKA INGIN MENDOWNLOAD FOLDER DIATAS SILAHKAN DI BAGIAN POJOK KANAN PILIH DOWNLOAD ZIP"

![ini](https://github.com/irma119/chatbot-deployment-unichat/assets/110200862/0e5745ef-f27a-4e93-a60d-de3b30438b7f)

## Jika ingin mengetahui lebih dalam silahkan tonton video berikut 
[![Alt text](https://img.youtube.com/vi/a37BL0stIuM/hqdefault.jpg)](https://youtu.be/a37BL0stIuM)  
[https://youtu.be/a37BL0stIuM](https://youtu.be/a37BL0stIuM)
