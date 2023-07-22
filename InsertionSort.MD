# Proje 1

```python
[22, 27, 16, 2, 18, 6]  # Insertion Sort
```

- **Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**
    
    - 1. Adım: [22, 27, 16, 2, 18, 6] -> [2, 27, 16, 22, 18, 6]
    - 2. Adım: [2, 27, 16, 22, 18, 6] -> [2, 6, 16, 22, 18, 27]
    - 3. Adım: [2, 6, 16, 22, 18, 27] -> [2, 6, 16, 22, 18, 27]
    - 4. Adım -> [2, 6, 16, 22, 18, 27] -> [2, 6, 16, 18, 22, 27]
    - 5. Adım -> [2, 6, 16, 18, 22, 27] -> [2, 6, 16, 18, 22, 27]
    - 6. Adım -> [2, 6, 16, 18, 22, 27] -> [2, 6, 16, 18, 22, 27]

- **Big-O gösterimini yazınız.**

    - Her eleman için yapılan toplam arama sayısını göz önünde bulundurarak şöyle bir işlem elde edebiliriz: _"n + (n-1) + .... + 1 "_
    - Bu işlem bize şu formülü verir: (n^2 + n) / 2
    - Bu formülü kullanarak Big-O gösterimini O(n^2) olarak buluruz.

- **Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız**

    - Average case: Aradığımız sayının ortada olması.
    - Worst case: Aradığımız sayının sonda olması.
    - Best case: Aradığımız sayının dizinin en başında olması.

        Aramanın Lineer Arama olduğunu göz önünde bulundurarak 18 sayısını bu algoritma ile aramanın **Average Case** olduğunu söyleyebiliriz



- **[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.**

    - 1. Adım: [7, 3, 5, 8, 2, 9, 4, 15, 6] -> [2, 3, 5, 8, 7, 9, 4, 15, 6]
    - 2. Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] -> [2, 3, 5, 8, 7, 9, 4, 15, 6]
    - 3. Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] -> [2, 3, 4, 8, 7, 9, 5, 15, 6]
    - 4. Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] -> [2, 3, 4, 8, 7, 9, 5, 15, 6]