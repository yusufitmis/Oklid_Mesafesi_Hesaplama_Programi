# Öklid Mesafesi Hesaplama Programı

Bu proje, Python dilinde 2D uzaydaki noktalar arasında Öklid mesafesini hesaplayan bir program içerir. Program, iki nokta arasındaki mesafeleri hesaplayarak minimum mesafeyi bulur ve çıktıyı ekrana yazdırır.

## Özellikler

- Bir liste içinde verilen noktalar arasında Öklid mesafesini hesaplar.
- Her nokta çifti arasındaki mesafeleri bir listeye kaydeder.
- Hesaplanan mesafelerden minimum olanını bulur ve ekrana yazdırır.

## Kullanılan Yapılar

- **Fonksiyonlar**: Mesafe hesaplamak için `euclideanDistance` adında bir fonksiyon kullanılır.
- **Döngüler**: Her nokta çifti için mesafeleri hesaplamak amacıyla iki iç içe döngü kullanılır.
- **Listeler**: Noktalar ve mesafeler listeler içinde tutulur.


## Örnek Kullanım

Noktalar şu şekilde tanımlanmıştır:

```python
points = [(1, 2), (4, 6), (5, 8), (3, 1), (7, 2)]


