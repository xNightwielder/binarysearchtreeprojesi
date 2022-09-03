# Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Root = 7. 
- 5 Sayısını Root'un sol tarafına yazıyoruz. Çünkü 5, 7'den küçüktür.
- 1 Sayısını Root'un soluna yazıyoruz fakat Root'un solunda bu sefer 5 var. Aynı şekilde 1 sayısı 5'ten küçük olduğu için bu sefer 5'in sol tarafına yazıyoruz.
- 8 sayısı Root'un sağ tarafına yazılır.
- 3 sayısı Root'un sol tarafına, sol tarafında 5 var. 3, 5'ten küçük olduğu için 5'in soluna fakat 5'in solunda 1 var. 3 sayısı 1'den büyük olduğu için 1 sayısının sağına yazılır.
- 6 sayısı Root'dan küçük 5'ten büyük olduğu için sağ tarafa
- 0 sayısı Root'dan küçük olduğu için sol tarafa geldik. 5'ten de küçük olduğu için tekrardan sol tarafa geldik.1'den de küçük olduğu için ve 1'in solunda bir şey olmadığı için 1'in sol tarafına yazıyoruz.
- 9 sayısı Root'dan ve 8'den büyük. 8'in sağ tarafında bir şey olmadığı için sağına yazıyoruz.
- 4 sayısı Root'dan 5'den küçük, 1'den ve 3'den büyük. 1'in sağında 3 var oraya yazamayacağız. 3'e geliyoruz. 3'ten büyük olduğu için ve 3'ün sağında herhangi bir şey olmadığı için 3'ün sağına  yazıyoruz.
- 2 sayısı Root'dan 5'den küçük, 1'den büyük, 3'den küçük. 2,5,+ ve 1'in her iki tarafı da (sağı ve solu) da dolu olduğu için 3'e geldik. 2, 3'ten küçük olduğu için ve 3 sayısının sol tarafı müsait olduğu için 3'ün soluna yazıyoruz.

## Görsel 

!["binarysearchtree image"](https://i.hizliresim.com/taodu91.png)
