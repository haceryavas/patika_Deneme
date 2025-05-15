# Binary Search Tree Projesi

## Hacer Nur Yavaş

- **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.**

Root 7'dir.
1. Adım: 5 ekleme. 7'den küçük olduğu için soluna eklenir.
2. Adım: 1 ekleme. 7'den ve 5'ten küçük olduğu için 5'in soluna yazılır
3. Adım: 8 ekleme. 7'den büyük olduğu için 7'nin sağına yazılır.
4. Adım: 3 ekleme. 7'den ve 5'ten küçük 1'den büyük olduğu için 1'in sağına yazılır.
5. Adım: 6 ekleme. 7'den küçük ve 5'ten büyük olduğu için 5'in sağına yazılır.
6. Adım: 0 ekleme. 7'den, 5'ten ve 1'den küçük olduğu için 1'in soluna yazılır.
7. Adım: 9 ekleme. 7'den ve 8'den büyük olduğu için 8'in sağına yazılır.
8. Adım: 4 ekleme. 7'den ve 5'ten küçük, 1'den ve 3'ten büyük olduğu için 3'ün sağına yazılır.
9. Adım: 2 ekleme. 7'den ve 5'ten küçük, 1'den büyük ve 3'ten küçük olduğu için 3'ün soluna yazılır.

                    7
                  /    \
                 5      8
               /   \      \
              1     6       9
            /   \
           0     3
               /   \
              2     4




