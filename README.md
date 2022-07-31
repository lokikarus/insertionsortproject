# insertionsortproject
patika.dev veri yapıları ve algoritmalar içeriği projesi

Proje 1
A) [22,27,16,2,18,6] -> Insertion Sort

a) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
b) Big-O gösterimini yazınız.
c) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
d) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

B) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.



A)
a) 1. [22,27,16,2,18,6]
   2. [2,27,16,22,18,6] 
   3. [2,6,16,22,18,27]
   4. [2,6,16,18,22,27]
b) O n^2
c)1. Average Case: [2,6,18,16,22,27] 
  2. Worst Case: [27,22,18,16,6,2]
  3. Best Case: [2,6,16,18,22,27]
d) Sıralanmış dizide 18 sayısı average case kapsamına girer.

B) 1. [7,3,5,8,2,9,4,15,6]
   2. [2,3,5,8,7,9,4,15,6]
   3. [2,3,4,8,7,9,5,15,6]
   4. [2,3,4,5,7,9,8,15,6]
   5. [2,3,4,5,6,9,8,15,7]
  
