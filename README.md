Java interview task to sort CVS file columns alphabetically.

1. Java function receives a CSV string as input and should return CSV string as output with columns sorted by name alpahbetically.
2. First line of file is a header with names.
3. Empty spaces should be interpreted as empty strings.
4. Lines separated by new line character "\n".
5. Only simple arrays can be used, Java Collections use is restricted.

Example input:
```
Jake,Allice,Bruce\n
12,65,45\n
545,345,878\n
65,7,67
```

Example Output:
```
Allice,Bruce,Jake\n
65,45,12\n
345,878,545\n
7,67,65
```
