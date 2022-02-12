# patika-insertion_sort_projesi

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. 
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

---

**1.**
```
          22, 27, 16, 2, 18, 6 -> n
1. Aşama: 2, 27, 16, 22, 18, 6 -> n-1
2. Aşama: 2, 6, 16, 22, 18, 27 -> n-2
3. Aşama: 2, 6, 16, 18, 22, 27 -> 1
```
**2.**
```
n + (n-1) + (n-2) + 1 = n.(n+1)/2 = (n²+n)/2 
O(n²)
```
**3.**
```
Best case     : Verilen dizinin küçükten büyüğe sıralanması
Avarage case  : Küçük sayıların ortada olması
Worst case    : Verilen dizinin büyükten küçüğe sıralı olması
```
**4.**
```
Case 3 - Avarage case
```

---

          7, 3, 5, 8, 2, 9, 4, 15, 6 -> n
1. Aşama: 2, 3, 5, 8, 7, 9, 4, 15, 6 -> n-1
2. Aşama: 2, 3, 4, 8, 7, 9, 5, 15, 6 -> n-2
3. Aşama: 2, 3, 4, 5, 7, 9, 8, 15 ,6 -> n-3
4. Aşama: 2, 3, 4, 5, 6, 9, 8, 15, 7 -> n-4

