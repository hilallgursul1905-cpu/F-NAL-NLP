# NLP Ödev 2 - Word2Vec Metin Benzerliği Analizi

## Proje Hakkında

Bu proje, Doğal Dil İşleme dersi kapsamında hazırlanmıştır. Çalışmada ürün yorumları üzerinde Word2Vec tabanlı metin benzerliği analizi gerçekleştirilmiştir.

## Veri Setleri

Projede aşağıdaki veri setleri kullanılmıştır:

* ham_veri.csv
* lemmatized_veri.csv
* stemmed_veri.csv

## İçerik

Bu proje kapsamında:

* Veri ön işleme işlemleri gerçekleştirilmiştir.
* Lemmatization ve stemming uygulanmıştır.
* CBOW ve Skip-Gram mimarileri kullanılmıştır.
* 16 farklı Word2Vec modeli eğitilmiştir.
* Cosine Similarity hesaplamaları yapılmıştır.
* Jaccard Similarity matrisi oluşturulmuştur.
* Sonuçlar heatmap ile görselleştirilmiştir.

## Model Yapıları

### Lemmatized Modeller

* CBOW - Window 2 - Dimension 100
* CBOW - Window 2 - Dimension 300
* CBOW - Window 4 - Dimension 100
* CBOW - Window 4 - Dimension 300
* SkipGram - Window 2 - Dimension 100
* SkipGram - Window 2 - Dimension 300
* SkipGram - Window 4 - Dimension 100
* SkipGram - Window 4 - Dimension 300

### Stemmed Modeller

* CBOW - Window 2 - Dimension 100
* CBOW - Window 2 - Dimension 300
* CBOW - Window 4 - Dimension 100
* CBOW - Window 4 - Dimension 300
* SkipGram - Window 2 - Dimension 100
* SkipGram - Window 2 - Dimension 300
* SkipGram - Window 4 - Dimension 100
* SkipGram - Window 4 - Dimension 300

Toplam 16 adet Word2Vec modeli eğitilmiştir.

## Kullanılan Kütüphaneler

* pandas
* numpy
* gensim
* scikit-learn
* matplotlib
* seaborn
* zeyrek

## Çalıştırma

`NLP-ÖDEV1-ÜRÜN YORUMLARI.ipynb` dosyasını Jupyter Notebook veya Google Colab ortamında açarak çalıştırabilirsiniz.

## Çıktılar

* cosine_sonuclari.csv
* jaccard_matrix.csv
* Eğitilmiş Word2Vec modelleri
