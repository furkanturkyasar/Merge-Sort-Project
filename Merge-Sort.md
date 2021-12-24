# Merge-Sort-Project
Patika için yaptığım bölüm sonu merge-sort projesi

### Proje 2
[16,21,11,8,12,22] -> Merge Sort

1-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.

## Solutions

1-                [16,21,11,8,12,22]
              [16,21,11]   -   [8,12,22]
          [16] - [21,11]   -   [8] - [12,22]
      [16] - [21] - [11]   -   [8] - [12] - [22]
          [16] - [11,21]   -   [8] - [12,22]
              [11,16,21]   -   [8,12,22]
                  [8,11,12,16,21,22]
                  
  
  
2- O(n logn)
