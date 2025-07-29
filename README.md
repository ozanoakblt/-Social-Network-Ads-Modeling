# 👥 Sosyal Medya Reklamları ile Satın Alma Tahmini

Bu proje, [Kaggle - Social Network Ads Dataset](https://www.kaggle.com/datasets/rakeshrau/social-network-ads) veri seti kullanılarak, kullanıcıların reklamlar aracılığıyla satın alma davranışlarını tahmin etmeyi amaçlamaktadır. 

Temel sınıflandırma algoritmalarından **Logistic Regression** ile modelleme yapılmış ve veri dengesizliği **SMOTE** yöntemi ile giderilmiştir.

## 🔍 Proje Kapsamı

- Veri setinin incelenmesi ve EDA (Keşifsel Veri Analizi)
- Eksik veri kontrolü
- Ayırt edici özelliklerin belirlenmesi
- SMOTE ile sınıfların dengelenmesi
- Logistic Regression ile model eğitimi
- Modelin başarı metrikleriyle değerlendirilmesi

## 🧪 Kullanılan Yöntemler

- **Logistic Regression**
- **SMOTE** (Synthetic Minority Over-sampling Technique)
- **Train-Test Split**
- **Standartlaştırma (StandardScaler)**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-score, Accuracy)**

## 📊 Model Başarı Sonuçları (SMOTE Uygulandıktan Sonra)

- Doğruluk Skoru: **%88.75**
- Karmaşıklık Matrisi:
- Sınıflandırma Raporu:

          precision    recall  f1-score   support

       0       0.92      0.90      0.91        52
       1       0.83      0.86      0.84        28

accuracy                           0.89        80


## 📁 Dosyalar

- `notebook.ipynb`: Tüm veri analizi, SMOTE uygulaması ve modelleme adımları bu notebook içinde yer almaktadır.
- `README.md`: Proje açıklaması
- `.gitignore`: Google Colab ve Jupyter dosyaları için yapılandırılmıştır.

## 📌 Not

Bu proje, eğitim ve portfolyo amaçlı hazırlanmıştır. Kullanılan veri seti [Kaggle](https://www.kaggle.com/datasets/rakeshrau/social-network-ads) üzerinden halka açık şekilde erişilebilmektedir.

## 📫 İletişim

Herhangi bir öneri, geri bildirim ya da soru için iletişime geçebilirsiniz.  
LinkedIn: [linkedin.com/in/ozan-akbulutt](https://www.linkedin.com/in/ozan-akbulutt)  
GitHub: [github.com/ozanakbulut](https://github.com/ozanakbulut)

---
