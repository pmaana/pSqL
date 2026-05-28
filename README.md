# pSqL

# AND, OR, NOR

```sql
SELECT * FROM ana WHERE th = 17 OR th = 16
```

AnA 부원중에 17기나 16기인 사람들을 가져오기

# UPPER
```sql
SELECT UPPER(name) FROM ana;
```

이름 대문자로 가져오기

# LOWER
```sql
SELECT LOWER(name) FROM ana;
```

이름 소문자로 가져오기

# LIMIT
```sql
SELECT * FROM ana LIMIT 5;
```

데이터 5개만 가져오기