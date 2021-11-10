[22,27,16,2,18,6] -> Insertion Sort

Soru 1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Soru 2) Big-O gösterimini yazınız.
Soru 3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Soru 4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


Soru 5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1)
* [22,27,16,2,18,6] > Insertion Sort
* [16,22,27,2,18,6]
* [2,16,22,27,18,6]
* [2,16,18,22,27,6]
* [2,6,16,18,22,27]

2) BigO: O(n^2)

3) Time Complexity:
     Best case: O(n) = O(6)
     Average case: O(n^2) = O(36)
     Worst case: O(n^2) = 0(36) 

4) Number 18 case : Average Case

5)
* [7,3,5,8,2,9,4,15,6] > Insertion Sort first 4 step
* [3,7,5,8,2,9,4,15,6]
* [3,5,7,8,2,9,4,15,6]
* [2,3,5,7,8,9,4,15,6]
* [2,3,4,5,7,8,9,15,6]