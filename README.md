# patika_dev_binary_search_tree

# Proje-3
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

**Root 7**

**5 sayısı 7'den küçük olduğu için 7'nin soluna ekledik**

                      7
                     / 
                    5

**1 sayısı 5'ten ve 7'den küçük olduğu için 7 ve 5'in soluna ekledik** 

                      7
                     / 
                    5   
                   / 
                  1 

**8 sayısı 7'den büyük olduğu için 7'nin sağına ekledik** 

                      7
                     / \
                    5   8
                   / 
                  1 
              
**3 sayısı  7'den ve 5'ten küçük olduğu için 5'in soluna, 1'den büyük olduğu için 1'in sağına ekledik**

                      7
                     / \
                    5   8
                   / 
                  1
                   \
                   3


**6 sayısı 7'den küçük olduğu için 7'nin soluna, 5'ten büyük olduğu için 5'in sağına ekledik**  

                      7
                     / \
                    5   8
                   / \   
                  1   6   
                  \
                   3


**0 sayısı  7'den, 5'ten ve 1'den küçük olduğu için 1'in soluna ekledik**  

                      7
                     / \
                    5   8
                   / \   
                  1   6   
                 / \
                0  3
                 

**9 sayısı  7'den ve 8'den büyük olduğu için  8'in sağına ekledik**  

                      7
                     / \
                    5   8
                   / \   \
                  1   6   9
                 / \
                0  3


**4 sayısı  7'den ve 5'ten küçük olduğu için 5'in soluna, 1'den ve 3'ten büyük olduğu için 3'ün sağına ekledik** 

                      7
                     / \
                    5   8
                   / \   \
                  1   6   9
                 / \
                0  3
                    \
                     4
 

**2 sayısı  7'den ve 5'ten küçük olduğu için 5'in soluna, 1'den büyük olduğu için 1'in sağına ve 3'ten küçük olduğu için 3'ün soluna ekledik** 

                      7
                     / \
                    5   8
                   / \   \
                  1   6   9
                 / \
                0  3
                  / \
                 2   4
