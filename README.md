 
  # NutriFit: Aplikasi Diet Cerdas
  
  Aplikasi diet pintar yang menyediakan rekomendasi makanan personal sesuai kebutuhan nutrisi dan preferensi pengguna.
</div>

---

## 📋 Deskripsi

NutriFit adalah aplikasi diet cerdas yang menggunakan machine learning untuk memberikan rekomendasi makanan yang dipersonalisasi berdasarkan kebutuhan kalori, preferensi makanan, dan tujuan diet pengguna. Aplikasi ini juga menyediakan fitur tracking makanan harian dan rekomendasi aktivitas fisik untuk membantu pengguna mencapai target berat badan mereka.

### ✨ Fitur Utama

- **Rekomendasi Makanan Personal**: Dapatkan rekomendasi makanan harian sesuai dengan kebutuhan kalori dan preferensi
- **Perhitungan Kebutuhan Kalori**: Kalkulasi otomatis kebutuhan kalori berdasarkan data fisik dan tujuan diet
- **Tracking Makanan**: Catat makanan yang dikonsumsi dan pantau asupan nutrisi harian
- **Rekomendasi Aktivitas Lari**: Dapatkan saran aktivitas lari sesuai dengan level kebugaran dan target
- **Analisis Progres**: Pantau kemajuan diet dengan visualisasi dan insights

## 🚀 Getting Started

### Prasyarat

- Python 3.8+
- Node.js 14+
- PostgreSQL 12+
- Git

### Instalasi

1. Clone repository ini

```bash
git clone https://github.com/username/nutrifit.git
cd nutrifit
```

2. Setup environment Machine Learning

```bash
cd ml
python -m venv venv
source venv/bin/activate  # Untuk Unix/MacOS
# atau
venv\Scripts\activate  # Untuk Windows
pip install -r requirements.txt
```

3. Setup Backend

```bash
cd ../backend
python -m venv venv
source venv/bin/activate  # Untuk Unix/MacOS
# atau
venv\Scripts\activate  # Untuk Windows
pip install -r requirements.txt
```

4. Setup Frontend

```bash
cd ../frontend
npm install
```

### Menjalankan Aplikasi

1. Jalankan Backend

```bash
cd backend
python src/app.py
```

2. Jalankan Frontend

```bash
cd frontend
npm start
```

## 🧠 Machine Learning

Model machine learning dalam aplikasi ini meliputi:

- **Kalkulasi Kebutuhan Kalori**: Menggunakan rumus Harris-Benedict dengan faktor aktivitas
- **Rekomendasi Makanan**: Algoritma yang menyusun menu seimbang berdasarkan kebutuhan nutrisi
- **Prediksi Perubahan Berat Badan**: Model thermodynamics untuk estimasi perubahan BB
- **Rekomendasi Aktivitas Fisik**: Algoritma untuk menentukan target lari berdasarkan level kebugaran

Detail implementasi dapat dilihat di folder `ml/`.

## 🛠️ Teknologi

- **Machine Learning**: Python, Pandas, NumPy, scikit-learn
- **Backend**: Flask/Django, PostgreSQL, SQLAlchemy
- **Frontend**: React.js, Redux, Chakra UI/Material UI
- **DevOps**: GitHub Actions, Docker

## 📊 Dataset

Aplikasi ini menggunakan dataset USDA FoodData Central yang telah dibersihkan dan diperkaya dengan makanan khas Indonesia.

## 📝 Roadmap

- [x] Persiapan dan cleaning dataset
- [ ] Pengembangan model ML
- [ ] Pengembangan backend API
- [ ] Pengembangan frontend
- [ ] Integrasi dan pengujian
- [ ] Deployment

Detail roadmap dapat dilihat di [docs/roadmap.md](docs/roadmap.md).

## 👥 Kontributor

- [Hafiyan Al Muqaffi Umary](https://github.com/habstrakT808/)

## 📄 Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT - lihat file [LICENSE](LICENSE) untuk detail.

## 📞 Kontak

Jika Anda memiliki pertanyaan, silakan hubungi [jhodywiraputra@gmail.com](mailto:jhodywiraputra@gmail.com).
