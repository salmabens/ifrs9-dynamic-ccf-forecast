# 📊 Modélisation Forward-Looking du CCF IFRS 9

## 📖 Description
Ce projet propose une méthodologie pour rendre dynamique le Credit Conversion Factor (CCF) dans le cadre d’IFRS 9, en intégrant des scénarios macroéconomiques (PIB, chômage, inflation, immobilier) et en projetant le CCF sur trois ans.

## 🚀 Fonctionnalités
- 🔄 Extraction et préparation des séries CCF et macroéconomiques  
- 🔍 Analyse exploratoire et tests de stationnarité/cointégration  
- 📈 Modèles globaux (OLS, SARIMA, VAR, ARIMAX)  
- 🧩 Modélisation segmentaire (ARIMA/SARIMAX, VECM)  
- 📆 Projections trimestrielles sous trois scénarios (optimiste, central, pessimiste) 

## 📂 Structure des fichiers
```
/Notebook                       # Notebook principal
/Rapport                        # Rapport du projet
/Présentation                   # Présentation du projet
/README.md                      # Documentation du projet
```
## 🚀 Comment Exécuter le Projet  

### 1️⃣ **Exécuter le Notebook sur Google Colab**  
Les fichiers étant volumineux, nous recommandons d'utiliser **Google Colab**.  

### 2️⃣ **Ajouter les Données sur Google Drive**  
- Créez un dossier nommé **"Data"** dans votre Google Drive.  
- Importez les fichiers de données dans ce dossier.  

### 3️⃣ **Monter Google Drive dans Colab**  
Ajoutez ce code dans votre notebook pour accéder aux données :  

```python
from google.colab import drive
drive.mount('/content/drive')

data_path = "/content/drive/My Drive/Data/"
```
