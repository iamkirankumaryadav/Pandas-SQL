<p align=center><img src='Pandas.png' width=25%></p>

### Pandas and SQL Equivalents

### SELECT

```SQL
SELECT Bill, Tip, Smoke, Meal
FROM Tips
LIMIT 5;
```

```Python
Tips[['Bill','Tip','Smoke','Meal']].head()
```

