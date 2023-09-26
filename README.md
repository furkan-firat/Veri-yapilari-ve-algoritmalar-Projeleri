# Veri-yapilari-ve-algoritmalar-Projeleri
Patikadev Frontend Dev Path Veri Yapilari ve Algoritmalar Proje 1-2-3 Çözümü

# Proje 1 - Insertion Sort

[22,27,16,2,18,6] -> Insertion Sort

1. Adım [22,27,16,2,18,6]
2. Adım [2,27,16,22,18,6]
3. Adım [2,6,16,22,18,27]
4. Adım [2,6,16,18,22,27]

# Big-O Gösterimi
Big-O = n^2 

# Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? 

Aradığımız sayı dizinin ortasında. Average case.

# [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] -> [2,3,5,8,7,9,4,15,6] -> [2,3,4,8,7,9,5,15,6] -> [2,3,4,5,7,9,8,15,6] -> [2,3,4,5,6,9,8,15,7]

   
----------------------------------

# Proje 2 - Merge Sort
,
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.



##  [16,21,11,8,12,22] -> Merge Sort
            [16,21,11,8,12,22]
    [16,21,11]          |  [8,12,22]

    [16,21]   [11]      |  [8,12]   [22]

    [16]   [21]   [11]  |  [8]   [12]   [22]  
 
    [16,21]   [11]      |  [8,12]   [22]

    [11,16,21]          |  [8,12,22]

    [8,11,12,16,21,22]

## Big-O 
O(n*logn)

----------------------------------

# Proje 3 - Binary Search Tree
# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

# 
root 7'dir.

5 -> Root düğümün solunda yer alır.
1 -> 5'in solunda yer alır.
8 -> Root düğümün sağına eklenir.
3 -> 5'in solunda yer alır.
6 -> 5'in sağına eklenir.
0 -> 1'in solunda yer alır.
9 -> 8'in sağına eklenir.
4 -> 3'ün sağına eklenir.
2 -> 1'in sağına eklenir.

            7
           / \
          5   8
         / \   \
        1   6   9
       / \
      0   3
         / \
        2   4
