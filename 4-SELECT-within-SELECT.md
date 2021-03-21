1. List each country name where the population is larger than that of 'Russia'.
```SQL
SELECT name 
FROM world
WHERE population >
  (SELECT population 
   FROM world
   WHERE name='Russia');
```

2. Show the countries in Europe with a per capita GDP greater than 'United Kingdom'.
```SQL
SELECT name 
FROM world
WHERE continent='Europe' AND
gdp/population >
  (SELECT gdp/population 
   FROM world
   WHERE name='United Kingdom');
```

3. List the name and continent of countries in the continents containing either Argentina or Australia. Order by name of the country.
```SQL

```

4.
```SQL

```

5.
```SQL

```

6.
```SQL

```

7.
```SQL

```

8.
```SQL

```

9.
```SQL

```

10.
```SQL

```
