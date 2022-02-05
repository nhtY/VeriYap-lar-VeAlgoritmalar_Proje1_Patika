# VeriYap-lar-VeAlgoritmalar_Proje1_Patika
Kodluyoruz eğitimi kapsamında veri yapıları ve algoritmalar eğitimi projesi.

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
---
## Cevaplar:
1. 16 22 27 2 18 6 --> 16 22 27 2 18 6 --> 16 22 27 2 18 6 --> 2 16 22 27 18 6 --> 2 16 18 22 27 6 --> 2 6 16 18 22 27
2. n + (n-1) + ... + 1 = n*(n+1)/2 = (n^2 + n) /2 ==> O(n^2)
3. Time Complexity:
* average case: n/2 comparison ==> O(n)
* worst case: n comparison ==> O(n)
* best case: 1 comparison ==> O(1) sabit
4. sıralı dizi : [2 6 16 18 22 27] ise 18 için average case.
5. [7,3,5,8,2,9,4,15,6] 
    1. 3 7 5 8 2 9 4 15 6
    2. 3 5 7 8 2 9 4 15 6 
    3. 3 5 7 8 2 9 4 15 6
    4. 2 3 5 7 8 9 4 15 6



