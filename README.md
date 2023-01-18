# merge-sort-project

[16,21,11,8,12,22] 
-------------
ilk olarak sayı dizimizi aşağıdaki gibi 2 eşit parçaya ayırıyoruz.
[16,21,11]       [8,12,22]
------------
Soldaki sayı dizisini, başındaki sayı ve geri kalanı olarak ayırıyoruz. Sağdaki sayı dizisini, sondaki sayı ve geri kalanı olarak ayırıyoruz.
[16]    [21,11]                    [8,12]   [22]
-------------
Kalan 2'li parçaları kendi arasında küçükten büyüğe olacak şekilde sıralıyoruz.
[16]    [11,21]                    [8,12]   [22]
--------------
Sağ ve soldaki sayı öbeklerini kendi aralarında küçükten büyüğe olacak şekilde sıralayıp birleştiriyoruz.
[11,16,21]                         [8,12,22]
--------------
Son olarak bu iki öbeği küçükten büyüğe sıralayarak birleştiriyoruz.
[8,11,12,16,21,22] 
---------------


Big-O gösterimi;
O(nlogn)
