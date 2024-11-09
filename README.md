# Credit-Card-Fraud-Detection
Ce projet est axé sur la détection des transactions frauduleuses par carte de crédit en utilisant un dataset public disponible sur Kaggle. Le dataset contient des transactions effectuées par des détenteurs de cartes européens en septembre 2013. Ce dataset est fortement déséquilibré, avec seulement 0,172 % des transactions identifiées comme frauduleuses

# Aperçu du Dataset
- Source : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download
- Contexte des Données : Les données ont été anonymisées en utilisant une Analyse en Composantes Principales (ACP) pour des raisons de confidentialité. Seules les caractéristiques Time et Amount n'ont pas été transformées.
- Contenu : Le dataset comprend 284 807 transactions sur deux jours, dont 492 sont étiquetées comme frauduleuses.
Caractéristiques :
- V1 à V28 : Composantes principales obtenues via l’ACP.
- Time : Secondes écoulées entre chaque transaction et la première transaction du dataset.
- Amount : Montant de la transaction, qui peut être utilisé pour un apprentissage sensible aux coûts.
- Class : Variable cible ; 1 indique une fraude et 0 une transaction légitime.
# Objectif
L'objectif principal de ce projet est d'identifier les transactions frauduleuses avec la meilleure précision possible, en tenant compte du fort déséquilibre des classes.
