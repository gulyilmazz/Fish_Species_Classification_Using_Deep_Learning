# Fish_Species_Classification_Using_Deep_Learning
# Balık Sınıflandırma Projesi

Bu proje, Akbank Derin Öğrenme Bootcamp kapsamında geliştirilmiştir. Kaggle'daki 'A Large Scale Fish Dataset' veri seti kullanılarak farklı balık türlerini sınıflandırmak için bir Yapay Sinir Ağı (ANN) modeli oluşturulmuştur.

## Proje İçeriği

Bu projede, aşağıdaki adımlar gerçekleştirilmiştir:

### 1. Veri Önişleme

Balık görüntüleri uygun formatta işlenmiş ve eğitim ile test setlerine ayrılmıştır. Görüntü boyutları ayarlanmış ve normalizasyon uygulanmıştır. Veri artırımı (data augmentation) ile modelin genel performansı artırılmıştır.

### 2. Model Oluşturma

Yapay Sinir Ağı (ANN) modeli oluşturulmuştur. Model, giriş katmanı, gizli katmanlar ve çıkış katmanından oluşmaktadır. Modelin katmanları dikkatlice seçilerek farklı balık türlerini ayırt etme yeteneği artırılmıştır.

### 3. Model Eğitimi

Model, eğitim seti üzerinde eğitilmiş ve doğrulama seti ile performansı değerlendirilmiştir. Eğitim sürecinde kayıp ve doğruluk değerleri izlenmiştir.

### 4. Sonuçların Değerlendirilmesi

Modelin test verisi ile değerlendirilmesi yapılmış, doğruluk ve kayıp değerleri hesaplanmıştır. Ayrıca, modelin sınıflandırma başarısını gösteren karmaşık matris ve sınıflandırma raporu oluşturulmuştur.

[Kaggle Notebook Linki] https://www.kaggle.com/code/ltfiyeglyilmaz/annfish-species-classification-using-deep-learning


****************************************************************************************************ENGLISH************************************************************************************************************
# Fish Classification Project

This project was developed as part of the Akbank Deep Learning Bootcamp. A Neural Network (ANN) model has been created to classify different fish species using the 'A Large Scale Fish Dataset' available on Kaggle.

## Project Overview

The following steps were performed in this project:

### 1. Data Preprocessing

Fish images were processed into the appropriate format and divided into training and test sets. Image sizes were adjusted, and normalization was applied. Data augmentation techniques were used to enhance the model's performance.

### 2. Model Creation

A Neural Network (ANN) model was built, consisting of an input layer, hidden layers, and an output layer. The architecture of the model was carefully designed to improve the ability to distinguish between different fish species.

### 3. Model Training

The model was trained on the training set and evaluated with the validation set. Loss and accuracy metrics were monitored during the training process.

### 4. Evaluation of Results

The model was evaluated using the test data, calculating accuracy and loss values. Additionally, a confusion matrix and classification report were generated to show the classification performance of the model.

### Links https://www.kaggle.com/code/ltfiyeglyilmaz/annfish-species-classification-using-deep-learning
