# Veri-Yapilari-ve-Algoritmalar
Insertion sort, Merge sort ve Binary search tree projeleri
# Proje 1
## [22,27,16,2,18,6] -> Insertion Sort
1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
En basit sorting algoritmalarından biridir. Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor. Sonrasında ikinci en küçük elemanı buluyor ve 2. sıra ile değiştiriyor. Baktık ki 2. sırada ki eleman en küçük hiç dokunmuyoruz. 4. 5. derken bu şekilde dizi bitirilir.

### [**2**,27,16,22,18,6]

### [**2**,**6**,16,22,18,27]

### [**2**,**6**,**16**,22,18,27]

### [**2**,**6**,**16**,**18**,22,27]

2) Big-O gösterimini yazınız.

n+(n-1)+...+1 = n*(n+1)/2 = n^2+n/2

O zaman O(n^2)

3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Aradığımız 18 sayısı dizi de orta da olduğu için Avarege case kapsamına girer.

5) ## [7,3,5,8,2,9,4,15,6] 
dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

### [**2**,3,5,8,7,9,4,15,6]

### [**2**,**3**,5,8,7,9,4,15,6]

### [**2**,**3**,**4**,8,7,9,5,15,6]

### [**2**,**3**,**4**,**5**,7,9,8,15,6]


