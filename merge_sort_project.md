# Merge Sort Project [patika.dev](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje)


**[16,21,11,8,12,22] -> Merge Sort**
## Questions

1. Write this array's sorting process step by step (Merge Sorting)
2. Write Big O View this array 
____

## Answer 1

1. Split this array. *New arrays: [16, 21,11], [8,12,22]*
2. Split these arrays again. *New arrays: [16,21],[11], [8,12],[22]*
3. Split these arrays again. *New arrays: [16],[21],[11],[8],[12],[22]*
4. Now sort all characters lower to bigger (lower ones comes left, bigger ones right) then merge them. *Example: 16 lower, 21 bigger. Merge them [16,21]*...
5. After merging process. *New arrays: [16,21], [8,11], [12,22]*
6. Keep merging twiced arrays. Pull lowest number in each array and write left. *New arrays: [8,11,16,21], [12,22]*
7. Keep merging again... *New array (final): [8,11,12,16,21,22]* 
8. [16,21,11,8,12,22] -> Merge Sorting -> [8,11,12,16,21,22]. All done!
___
## Answer 2

Big O View is O(nlogn)
___


