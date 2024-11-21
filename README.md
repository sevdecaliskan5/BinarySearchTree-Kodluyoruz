# Binary Search Tree

**Dizinin Binary Search Tree (BST) oluşturulma aşamaları:**

Başlangıç dizisi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Kök olarak ilk eleman olan 7^yi seçiyoruz. Sonra sağa doğru ilerliyoruz. 5 7'den küçük olduğu için 7'nin soluna yazılır. Daha sonra aynı işlem 1 için uygulanır. 1 7'den ve 5'ten küçüktür. O zaman 1 ikisin de solunda kalacak şekilde yazılır. 8 7'den büyük olduğu için 7'nin sağına yerleştirilir. Bu şekilde BST'nin tüm adımlarından sonra aşağıdaki yapı oluşmuş olur.

```
        7
       / \
      5   8
     / \   \
    1   6   9
   / \   
  0   3  
     / \
    2   4
```
