# Fuzzy-match-on-listed-companies
The aim of this project is to pick the public companies(have listed on American stock exchanges) from the original 222,450 companies(some are repeated).

### Fuzzy_match_of_public
- Wang Jin & Zhongjie He

#### Problem describtion
The aim of this project is to pick the public companies(have listed on American stock exchanges) from the original 222,450 companies(some are repeated). The file **work1.csv** is the work file and the **work2** is the public companies(more than 6,000) in United States' share exchanges. Mainly we apply *fuzzy wuzzy* algorithm and picked the required ones. https://github.com/seatgeek/fuzzywuzzy (developped by SeatGeet)

**There are two main difficulties. **
- The first names in the file with unchecked companies are not very formal, say **'Apple company '** instead of **'Apple Inc'**. We designed the *fuzzy wuzzy* value by making experiments manually in advance. 
- The second is massive data leads to much running time (it is estimated more than **12 hours** for the first version programe). We reduced it to **less than five minutes** by devide the matching procedure into two steps after carefully observed the data structure.


