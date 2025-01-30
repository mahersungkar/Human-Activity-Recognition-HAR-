🚶‍♂️ Human Activity Recognition (HAR) Classification
📌 Overview
Proyek ini bertujuan untuk mengklasifikasikan aktivitas manusia seperti berdiri, berjalan, berlari, dan lainnya menggunakan data sensor dari perangkat wearable atau ponsel pintar. Data ini dikumpulkan dari akselerometer dan giroskop yang ditempelkan pada tubuh manusia.

📂 Dataset lengkap dapat diakses di sini: Human Activity Recognition Dataset

📁 Dataset Information
Dataset ini berisi data sensor yang dikumpulkan dari 30 partisipan yang melakukan aktivitas tertentu saat mengenakan perangkat wearable. Beberapa fitur utama dalam dataset ini:

Time Domain Features: Data akselerasi dan kecepatan sudut dalam domain waktu.
Frequency Domain Features: Transformasi Fourier dari sinyal sensor.
Activity Labels: Berdiri, berjalan, berlari, duduk, naik tangga, turun tangga, dll.
📌 Tujuan Proyek:

Membangun model klasifikasi untuk mengenali aktivitas manusia berdasarkan data sensor.
Mengevaluasi performa model dengan berbagai algoritma Machine Learning.
🛠 Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, TensorFlow/Keras)
Jupyter Notebook
Machine Learning (Random Forest, SVM, Neural Networks)
Deep Learning (LSTM, CNN for Time-Series Data)
📊 Exploratory Data Analysis (EDA)
✅ Distribusi data berdasarkan jenis aktivitas.
✅ Visualisasi pola data sensor dalam domain waktu dan frekuensi.
✅ Analisis hubungan antar fitur sensor menggunakan correlation heatmap.

🚀 Model Development
Model yang digunakan dalam klasifikasi aktivitas manusia:
✅ Random Forest – Untuk baseline model.
✅ Support Vector Machine (SVM) – Untuk menangani data berdimensi tinggi.
✅ LSTM (Long Short-Term Memory) – Untuk menangkap pola sekuensial dalam data sensor.
✅ CNN (Convolutional Neural Network) – Untuk mengekstrak fitur dari sinyal sensor.

📌 Evaluasi Model:

Accuracy, Precision, Recall, F1-Score
Confusion Matrix untuk melihat kesalahan klasifikasi
ROC Curve untuk model klasifikasi
📜 How to Use
Clone repository ini:
bash
Salin
Edit
git clone https://github.com/username/human-activity-recognition.git
Install dependencies:
bash
Salin
Edit
pip install -r requirements.txt
Jalankan analisis di Jupyter Notebook:
bash
Salin
Edit
jupyter notebook
🤝 Contributing
Jika Anda ingin berkontribusi, silakan fork repository ini, buat branch baru, dan ajukan pull request! 🚀

📩 Contact
📧 Email: sungkarmaher6@gmail.com
🔗 LinkedIn: Maher Ismail Sungkar
