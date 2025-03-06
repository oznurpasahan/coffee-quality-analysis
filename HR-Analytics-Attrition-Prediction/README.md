"# HR Analytics - Attrition Prediction" 
# 🏢 HR Analytics - Çalışan Ayrılma Tahmini (Attrition Prediction)

📊 **Makine öğrenmesi ile çalışanların işten ayrılma durumlarını tahmin etmek mümkün mü?**  
Bu projede IBM HR Analytics veri seti ile çalışanların ayrılma eğilimlerini tahmin eden bir **makine öğrenmesi modeli** geliştirdim.  

---

## 📌 **Proje Hakkında**  

Bu proje, çalışanların işten ayrılma olasılığını tahmin etmek amacıyla geliştirilmiştir. **İnsan Kaynakları (HR) departmanları**, çalışan kaybını en aza indirmek için bu tür tahmin modellerinden yararlanabilir.  

📌 **Veri Seti:** [IBM HR Analytics Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  
📌 **Notebook:** [Kaggle Proje Linki](https://www.kaggle.com/code/znurpaahan/hr-analytics-al-an-ayr-lma-tahmini-attrition)  
📌 **Kullanılan Kütüphaneler:** Pandas, NumPy, Seaborn, Scikit-Learn, Imbalanced-Learn, Matplotlib  

---

## 🚀 **Kullanılan Teknikler**  
✅ **Keşifsel Veri Analizi (EDA)**  
✅ **Eksik ve dengesiz veri analizi**  
✅ **Özellik mühendisliği (Feature Engineering)**  
✅ **SMOTE ile veri dengeleme**  
✅ **Makine öğrenmesi modelleri (Logistic Regression, Decision Tree, Random Forest)**  
✅ **Hyperparameter Tuning (GridSearchCV) ile en iyi model seçimi**  
✅ **Model başarım analizi (Confusion Matrix, Feature Importance, Recall, Precision)**  

---

## 📈 **Model Performansı**  

- **Final Model Accuracy (Doğruluk):** **%87.4**  
- **Recall (Duyarlılık) Artışı:** **%5 → %41** 📈  
- **F1-Score İyileşmesi:** **0.10 → 0.46**  
- **Çalışan ayrılma tahminlerinde doğruluk 8 kat artırıldı.** 🎯  

**📊 Model Başarı Grafikleri:**  
Confusion Matrix ve Feature Importance sıralaması, tahmin gücümüzü artırmak için analiz edildi.  

---

## 📂 **Proje Dosyaları**  
🔹 `HR_Analytics_Attrition_Prediction.ipynb` → Notebook dosyası  
🔹 `README.md` → Proje açıklaması  

---

## 💡 **Nasıl Çalıştırılır?**  
Projeyi çalıştırmak için:  

```bash
git clone https://github.com/kullanici_adin/HR-Analytics-Attrition-Prediction.git
cd HR-Analytics-Attrition-Prediction
pip install -r requirements.txt
jupyter notebook
