# merge_sort_project

## SORU:
[16,21,11,8,12,22] -> merge sort
- yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

## CEVAP:
    [16,21,11,8,12,22]
[16,21,11]  [8,12,22] -> 1. Adım
[16], [21,11],    [8], [12,22] -> 2. Adım
Diziyi böldüğümüz şekilde küçükten büyüğe sıralıyoruz. [11,16,21], [8,12,22] -> 3. Adım
Bölmüş olduğumuz ve kendi içlerinde küçükten büyüğe sıralama yaptığımız dizileri birleştirip bu sefer bir bütün halinde küçüten büyüğe sıralama yapıyoruz. [8,11,12,16,21,22] -> 4. Adım

Big-O gösterimi : 2^x=n olacağından, logn=x olur. Eleman bazlı (n) şekilde gittiğimizden dolayı da Big-O Gösterimi = O(nlogn) olur.
