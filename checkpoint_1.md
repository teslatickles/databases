1. 1. string
   2. integer
   3. date 
   4. float
   5. string

1. A text file should be used when the data that needs to persist will only be interacted with locally and likely will not be interacted with by multiple users. A database would be used when more flexible management of the data are needed and multiple users will interact and manipulate that data.Also, with a database there is an application/interface that allows access to data outside of your project application that accesses the data.

1. One difference between SQL and many other programming languages is that SQL is a declarative language--user declares what they want and the language does the best it can to satisfy that request. Many languages, such as Javascript, are considered _procedural_ languages, and require developers to make best use of their skills to write out the _procedures_ needed to achieve the desired result. 

1. The data that makes up a database is displayed in a table that have columns representing disparate/different characteristics, values, information that make up single rows that are counted as both a single entity itself, which represents one unit the collective values of the different columns. Rows are what group the different types of data/represented things into one unit. (I'm not sure what the question is asking?) -- need some help! thanks

1. A _table_ is where data is stored and displayed, with _columns_ denotingthe particular data in the collection of data for a complete conceptual unit--one complete conceptual unit is denoted by a single _row_. A _value_ is some piece of data/information that exists at the intersection of the appropriate kind of data (column) and appropriate complete row in question that contains a collection of data.   

1. `Date`, `Integer`, `Object`

1. Select two columns, `dates` and `amounts` in the `payments` table, and return/display a new table including those selected `dates` and `amounts`.

dates
-----
2016-05-01
2016-05-10
2016-05-15 
2016-05-23

amount
------
1500.00
37.00 
124.93
54.72 

Select ANY value from `amounts` column in `payments` table where `amount` is greater than 500, and RETURN new table with `amount` - 1500.00.


amount
------
1500.00


Select All columns from `payments` table where `payee` is `Megafoods`, and RETURN new table with a row matching search.

'2016-05-15', 'Mega Foods', 124.93, 'Groceries'

8. ```
SELECT email, signup
FROM users
WHERE name = 'DeAndre Data';

'datad@comcast.net', '2008-01-20'
```

```
SELECT userid
FROM users
WHERE email = 'aleesia.algorithm@uw.edu';

userid
------
1
```

```
SELECT *
FROM users
WHERE userid = 4;

4,       'Brandy Boolean',    'bboolean@nasa.gov',            '1999-10-15'
```
