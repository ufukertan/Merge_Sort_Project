# Merge_Sort_Project

[16,21,11,8,12,22]  sayılarından oluşan diziyi Merge Sort algoritması kullanarak sıralayalım:

Diziyi ikiye bölerek yeniden yazarız:

[16,21,11] ve [8,12,22]

Şimdi sol ve sağdaki dizileri tekrar ikiye böleriz:

[16] - [21,11] - [8] - [12,22]

şimdi tek eleman kalana kadar bir kez daha bölüyoruz:

[16] - [21] - [11] - [8] - [12] - [22]

şimdi ikili ikili sıralayarak birleştiriyoruz:

[16] - [21,11] - [8] - [12,22]

şimdi bu ikilileri birleştiriyoruz:

[11,16,21] - [8,12,22]

şimdi bu son dizileri birleştiriyoruz ve sıralanmış dizimizi elde ediyoruz:

[8,11,12,16,21,22]

Big-O Notation:

O(nlogn)
