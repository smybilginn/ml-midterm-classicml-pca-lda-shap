# ml-midterm-classicml-pca-lda-shap
Machine Learning project comparing classical models with PCA, LDA and SHAP explainability analysis.

# Makine Öğrenmesi Ara Sınav Projesi | Classification, PCA, LDA ve SHAP Analizi

Bu projede, bir sınıflandırma problemi kapsamında klasik makine öğrenmesi algoritmaları kullanılarak kapsamlı bir analiz gerçekleştirilmiştir.

Çalışmada ham veri, PCA (Principal Component Analysis) ve LDA (Linear Discriminant Analysis) olmak üzere üç farklı veri temsili kullanılarak modellerin performansları karşılaştırılmıştır. Modeller, validation ve test veri setleri üzerinde Accuracy, Precision, Recall, F1-score ve ROC-AUC metrikleri ile değerlendirilmiştir.

Ayrıca modelin karar mekanizmasını açıklamak amacıyla SHAP (SHapley Additive exPlanations) yöntemi kullanılarak açıklanabilir yapay zeka (XAI) analizi yapılmıştır.

## Kullanılan Modeller
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier
- Gaussian Naive Bayes

## Uygulanan Yöntemler
- Veri Ön İşleme (Preprocessing)
- Ölçeklendirme (StandardScaler)
- Boyut İndirgeme (PCA ve LDA)
- Model Eğitimi ve Karşılaştırma
- SHAP ile Model Açıklanabilirliği

## En İyi Model
Random Forest (Ham Veri)

## Sonuç
Elde edilen sonuçlara göre Random Forest algoritması en yüksek performansı göstermiştir. PCA ile veri boyutu azaltılmasına rağmen performans büyük ölçüde korunmuştur. LDA yöntemi görsel olarak sınıf ayrımını başarılı bir şekilde gösterse de model performansı açısından diğer yöntemlerin gerisinde kalmıştır.

SHAP analizi, modelin kararlarını tümörün büyüklüğü ve şekli ile ilişkili özelliklere dayandırdığını göstermiştir.
