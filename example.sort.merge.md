### sorting/merge_sort
```
ycheng@nuc:/mnt/sdb/Data/learn/github/Algorithm_And_Data_Structure/sorting$ ./merge_sort.py
[ Ascending sort ]
--------------------------------------------------------------------------------
- input   : [16, 2, 13, 5, 11, 8, 9, 14, 17, 4, 1, 12, 18, 7, 15, 10, 3, 6]
[2, 16], count: 0
[5, 13], count: 1
[16, 2, 13, 5], count: 2
[8, 11], count: 3
[9], count: 4
[14, 17], count: 5
[9, 14, 17], count: 6
[11, 8, 9, 14, 17], count: 7
[16, 2, 13, 5, 11, 8, 9, 14, 17], count: 8
[1, 4], count: 9
[12, 18], count: 10
[4, 1, 12, 18], count: 11
[7, 15], count: 12
[10], count: 13
[3, 6], count: 14
[10, 3, 6], count: 15
[7, 15, 10, 3, 6], count: 16
[4, 1, 12, 18, 7, 15, 10, 3, 6], count: 17
[16, 2, 13, 5, 11, 8, 9, 14, 17, 4, 1, 12, 18, 7, 15, 10, 3, 6], count: 18
- output  : [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18]

[ Descending sort ]
--------------------------------------------------------------------------------
- input   : [16, 2, 13, 5, 11, 8, 9, 14, 17, 4, 1, 12, 18, 7, 15, 10, 3, 6]
[16, 2], count: 19
[13, 5], count: 20
[16, 2, 13, 5], count: 21
[11, 8], count: 22
[9], count: 23
[17, 14], count: 24
[9, 14, 17], count: 25
[11, 8, 9, 14, 17], count: 26
[16, 2, 13, 5, 11, 8, 9, 14, 17], count: 27
[4, 1], count: 28
[18, 12], count: 29
[4, 1, 12, 18], count: 30
[15, 7], count: 31
[10], count: 32
[6, 3], count: 33
[10, 3, 6], count: 34
[7, 15, 10, 3, 6], count: 35
[4, 1, 12, 18, 7, 15, 10, 3, 6], count: 36
[16, 2, 13, 5, 11, 8, 9, 14, 17, 4, 1, 12, 18, 7, 15, 10, 3, 6], count: 37
- output  : [18, 17, 16, 15, 14, 13, 12, 11, 10, 9, 8, 7, 6, 5, 4, 3, 2, 1]
```