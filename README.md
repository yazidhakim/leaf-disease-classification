# 🌱 Leaf Disease Classification

📌 Deskripsi

Proyek ini mengembangkan model deep learning berbasis Convolutional Neural Network (CNN) untuk mengklasifikasikan penyakit pada daun tanaman. Dataset berisi gambar daun yang terbagi dalam beberapa kelas penyakit serta kelas healthy. Model diekspor ke format SavedModel / TFLite agar bisa digunakan pada aplikasi lebih lanjut (mobile/web/IoT).

📊 Dataset

Sumber: [Plant Leaf Disease from Roboflow]

Jumlah kelas: 6

Yellow_Leaf_Curl_Virus

Black_measles

Healthy

Leaf_sorch

Mildew

Scab

Dataset dibagi menjadi train, validation, dan test set untuk memastikan generalisasi model.

🧠 Model

Arsitektur: CNN (Convolutional Neural Network)

Preprocessing: resize gambar ke (224,224), normalisasi piksel [0,1].

Optimizer: Adam

Loss: categorical crossentropy

Metrics: accuracy

📈 Hasil

Akurasi training: 96,48%

Akurasi validasi: 86,54%

Akurasi test: 84,61%
