# Proje-cevaplar-
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Soru 1:
Insertion Sort turune gore asamalar:
1-[22,27,16,2,18,6]
2-[2,27,16,22,18,6]
3-[2,6,16,22,18,27]
4-[2,6,16,18,22,27]

sirali bir sekile gelmis oldu.

18 sayisi Insertion sort yaptigimiz icin worst case scenario'ya girer.
Cunku algoritma listeye bastan basladigini ve sirali ilerledigi icin siranin sonunda bulunan 18'e ulasmasi zaman alacaktir

Soru 2:
Insertion Sort'a göre ilk 4 adımı:
1-[7,3,5,8,2,9,4,15,6] 
2-[2,3,5,8,7,9,4,15,6] 
3-[2,3,4,8,7,9,5,15,6]
4-[2,3,4,5,7,9,8,15,6]
5-[2,3,4,5,6,9,8,15,7]


Proje 2:
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


Diziyi 2'ye boluyoruz.
[16,21,11] [8,12,22]
Bu dizileri kendi aralarında tekrar ikiye boluyoruz.
[16,21] [11] [8,12] [22]
Tum dizileri tek eleman kalana kadar bolmeye devam ediyoruz.	
[16] [21] [11] [8] [12] [22]
Bolme islemini bitirdikten sonra tum elemanlar karsilastirilip sirali bir dizi seklinde birlestiriliyor.	
[8,11,12,16,21,22]

Big-O = (nlogn) olarak karsimiza cikar
