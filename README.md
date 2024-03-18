[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22, 27, 16, 2, 18, 6] n

[2,| 22, 27, 16, 18, 6] n-1

[2, 6,| 22, 27, 16, 18] n-2

[2, 6, 16,| 22, 27, 18] n-3

[2, 6, 16, 18,| 22, 27] 1

Big-O gösterimini yazınız.

Big-O: => Islemler n'den 1'e kadar gidecegi icin, 1'den n'e kadar olan sayilarin toplami sonucu verecektir.

n.(n+1)/2

= n^2

=> o(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması

Worst case: Aradığımız sayının sonda olması

Best case: Aradığımız sayının dizinin en başında olması.

Time Complexity: sıralama bu şekilde [6,2,16,18,22,27] olacağı için 6 = Lower , 27 = Higher ve 18 = Middle olacaktır. Bu durumda 18 sayısı Average Case için uygun oluyor.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[2,|3,5,8,7,4,15,6]

[2,3|,5,8,7,4,15,6]

[2,3,4|,8,7,5,15,6]

[2,3,4,5|,7,8,15,6]




[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

0 -> [16,21,11,8,12,22]
1 -> [16,21,11] ; [8,12,22]
2- > [16,21][11] ; [8,12][22]
3 -> [16][21] , [11,8] , [12,22]
4 -> [8,11,16,21] , [12,22]
5 -> [8,11,12,16,21,22]

Big-O:
O(nlogn)

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root = 7

         7
       /   \
      5     8
     / \     \
    1   6     9
     \   \   /
      3   0 4
       \
        2
