```
SELECT
 first_name,
        last_name
FROM
 customer
WHERE
 first_name LIKE 'Jen%';
 ```

 ```
 SELECT
  'foo' LIKE 'foo', -- true
  'foo' LIKE 'f%', -- true
  'foo' LIKE '_o_', -- true
  'bar' LIKE 'b_'; -- false
```
 
```
 SELECT
  first_name,
         last_name
 FROM
  customer
 WHERE
  first_name LIKE '%er%'

```
 
```
 SELECT
  first_name,
  last_name
 FROM
  customer
 WHERE
  first_name LIKE '_her%';
```
 
```
  SELECT
   first_name,
   last_name
  FROM
   customer
  WHERE
   first_name NOT LIKE 'Jen%';
```

```
 SELECT
  first_name,
  last_name
 FROM
  customer
 WHERE
  first_name ILIKE 'BAR%';
```
