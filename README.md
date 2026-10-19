# 🫁 Akciğer Kanseri Erken Teşhis ve Tahmin Sistemi (Lung Cancer Prediction System)

> Bu proje, makine öğrenmesi algoritmaları kullanarak bireylerin sağlık verileri ve tıbbi özellikleri üzerinden akciğer kanseri riskini tahmin etmek amacıyla **Google Colab** üzerinde geliştirilmiştir.

---

## 📋 İçindekiler
- [Proje Hakkında](#-proje-hakkında)
- [Kullanılan Teknolojiler ve Kütüphaneler](#-kullanılan-teknolojiler-ve-kütüphaneler)
- [Veri Seti ve Ön İşleme](#-veri-seti-ve-ön-işleme)
- [Model Eğitimi ve Değerlendirme](#-model-eğitimi-ve-değerlendirme)
- [Google Colab Üzerinde Çalıştırma](#-google-colab-üzerinde-çalıştırma)
- [Proje Mimarisi](#-proje-mimarisi)

---

## 🔍 Proje Hakkında
Erken teşhis, akciğer kanseri tedavisinde hayati bir önem taşır. Bu projede; hastaların demografik bilgileri, yaşam alışkanlıkları (sigara kullanımı vb.) ve klinik semptomları analiz edilerek risk durumunu yüksek doğrulukla sınıflandıran makine öğrenmesi modelleri geliştirilmiştir. 

---

## 🛠 Kullanılan Teknolojiler ve Kütüphaneler
Projede kullanılan temel araç ve kütüphaneler:

* **Geliştirme Ortamı:** Google Colab (Jupyter Notebook)
* **Programlama Dili:** Python
* **Veri Analizi & Manipülasyon:** Pandas, NumPy
* **Veri Görselleştirme:** Matplotlib, Seaborn
* **Makine Öğrenmesi Modelleri:** Scikit-Learn (XGBoost, Random Forest vb.)

---

## 📊 Veri Seti ve Ön İşleme
1. **Veri Yükleme:** Çeşitli tıbbi parametreleri içeren veri seti Google Colab ortamına aktarılmıştır.
2. **Veri Temizleme:** Eksik veya tutarsız veriler ayıklanmıştır.
3. **Özellik Mühendisliği (Feature Engineering):** Kategorik veriler sayısal formata dönüştürülmüş ve model başarısını artırmak için ölçeklendirme işlemleri yapılmıştır.

---

## ⚙️ Model Eğitimi ve Değerlendirme
Projede farklı sınıflandırma algoritmaları test edilmiş, model başarısını değerlendirmek için doğruluk (accuracy), kesinlik (precision), duyarlılık (recall) ve F1-skoru gibi metrikler kullanılmıştır.

---

## 🚀 Google Colab Üzerinde Çalıştırma

Projeyi incelemek veya yeniden çalıştırmak için şu adımları izleyebilirsiniz:

1. `notebooks/` klasöründeki veya projedeki `.ipynb` uzantılı dosyayı indirin.
2. [Google Colab](https://colab.research.google.com/) adresine gidin.
3. **Dosya -> Not Defteri Yükle** seçeneğini kullanarak dosyayı Colab'e yükleyin.
4. Hücreleri sırasıyla (`Runtime -> Run All`) çalıştırarak modeli test edin.

---

## 📂 Proje Mimarisi

```text
├── dataset/               # Projede kullanılan veri seti (.csv)
├── notebooks/             # Google Colab üzerinde hazırlanan Jupyter Notebook dosyaları
└── README.md              # Proje dokümantasyonu
