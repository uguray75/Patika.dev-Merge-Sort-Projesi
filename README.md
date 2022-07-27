# Patika.dev-Merge-Sort-Projesi
Patika.dev 'in "Veri Yapıları ve Algoritmalar" dersinin "Merge Sort Projesi" ödevidir.

# Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort
1-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.

# [16,21,11,8,12,22] dizisinin sort türüne göre aşamalarını yazınız.

                             [16,21,11,8,12,22]
                                  |      |
                           [16,21,11]   [8,12,22]
                           |        |     |     | 
                          [16]  [21,11] [8,12] [22]
                            |       |      |     |
                          [16][21][11] [8][12][22]
                            |   |   |    |  |   |
                          [16]  [11,21] [8,12] [22]
                            |       |      |     |
                           [11,16,21]   [8,12,22]
                                |           |
                             [8,11,12,16,21,22]
                             
                             
                             
                          
# [16,21,11,8,12,22] dizisinin Big-O gösterimi

Dizinin Big-O gösterimi O(nlogn) dir.

                             






