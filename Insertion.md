# Insertion Sort
### [ 22 , 27 , 16 , 2 , 18 , 6 ] :: insertion sorta göre sırala
##### 27, 22 ile karşılaştırılır. 27, 22'den büyük olduğu için yer değiştirmez.
* _Sıralı dizi_ : 22, 27, 16, 2, 18, 6
##### Üçüncü eleman 16, sıralı alt dizi içinde doğru konumunu bulana kadar ilerler. Önce 27 ile karşılaştırılır ve 27'den küçük olduğu için 27 sola kayar. Daha sonra 22 ile karşılaştırılır ve 22'den küçük olduğu için 22 sola kayar.
* _Sıralı dizi_ : 16, 22, 27, 2, 18, 6
##### Dördüncü eleman 2 , önce 27 ile karşılaştırılır ve 27'den küçük olduğu için sola kayar , daha sonra 22 ile karşılaştırılır ve 22'den küçük olduğu için yine sola kayar.Ardından 16 ile karşılaştırılır ve 16'dan da küçük olduğu için 16 sola kayar
* _Sıralı dizi_ : 2, 16, 22, 27, 18, 6
#####  Beşinci eleman 18 , önce 27 ile karşılaştırılır ve 27'den küçük olduğu için sola kayar , daha sonra 22 ile karşılaştırılır ve 22'den küçük olduğu için yine sola kayar. Ardından 16 ile karşılaştırılır ve 16'dan büyük olduğu için yer değiştirmez. Son olarak, 18, doğru konumuna yerleştirilir.
* _Sıralı dizi_ : 2, 16, 18, 22, 27, 6
##### Altıncı eleman 6, sıralı alt dizi içinde doğru konumunu bulana kadar ilerler.
* _Sıralı Dizi_ : 2, 6, 16, 18, 22, 27

---
### Big O gösterimi :: 
##### n + (n - 1) + (n - 2) + (n - 3) + (n - 4) + 1 = (n( n + 1 )) / 2 = n^2 
##### Big(O) = n^2
---
### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? ::
##### Aradığımız sayı dizinin ortasında olduğu için _Average Case_ olur
---
### [ 7 , 3 , 5 , 8 , 2 , 9 , 4 , 15 , 6 ] selection sorta göre sırala
##### 1. adım : [ 2* , 3 , 5 , 8 , 7* , 9 , 4 , 15 , 6 ]
##### 2. adım : [ 2 , 3 , 4* , 8 , 7 , 9 , 5* , 15 ,6 ]
##### 3. adım : [ 2 , 3 , 4 , 5* , 7 , 9 , 8* , 15 , 6 ]
##### 4. adım : [ 2 , 3 , 4 , 5 , 6* , 9 , 8 , 15 , 7*]
