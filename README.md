# Amaç
Bu proje, Aygaz Yapay Zekaya Giriş Bootcamp eğitimi sonunda verilen görev için hazırlanmıştır. Fashion MNIST veri seti, kıyafet görüntülerinden oluşur ve 10 farklı sınıfa ayrılmıştır.

## Giriş

Bu proje, Kaggle'dan alınan bir görüntü veri seti olan Fashion MNIST veri setini kullanarak çeşitli makine öğrenmesi algoritmaları ile nasıl ön işleme, sınıflandırma yapılacağını göstermektedir. Proje, Google Colab not defteri üzerinde gerçekleştirilmiştir ve veri yükleme, görselleştirme, normalleştirme, model eğitimi ve değerlendirme adımlarını içermektedir.

## İçindekiler

- [Giriş](#giriş)
- [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
- [Kurulum](#kurulum)

## Kullanılan Teknolojiler

- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow Keras
- Google Colab

## Kurulum
Fashion MNIST veri setini aşağıdaki kodla direkt google colab üzerinden kullanabilirsiniz.
```bash

(X_train, y_train), (X_test, y_test) = fashion_mnist.load_data()
```
Projeyi yerel makinenize klonlayın:
```bash
git clone https://github.com/nisaBayhan/fashion_mnist_data.git 
```
