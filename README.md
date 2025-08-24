"# Spark"
Funciones Fecha y Hora:

## SPARK FUNDAMENTALS

- Transformaciones y acciones
- RDD
- Almacenamiento en cache
- Particionado
- Mezcla de datos (Shuffling)
- Broadcast variables
- Acumuladores

### SPARK SQL

- Dataframes
- Catalyst Optimizer
- explain(True)

#### Funciones

- Select , SelectExp
- Filter, where
- Distinct, dropDuplicates
- Sort, orderBy
- withColumn, withColumnRenamed

#### --

- Leer y escribir archivo en AWS S3
- Persistencia de df (cache, persist, StorageLevel)

#### --

- Agregaciones (count, countDistinct, approx_count_distinct, min, max, sum, sumDistinct, avg)
- Agregaciones con pivot
- Join Expresions (left anti join, left semi join, ..)
- <span style="color:green">Shuffle join vs BroadCast join</span>

#### trabajo con fechas

- to_date(str,formato\*), to_timestamp(str,formato\*), format_date(date,format\*)
- date_diff(col, col)
- months_between()
- last_day(), date_add(), date_sub()
- Extraer valores: year,month,dayofmonth,dayofweek,dayofyear,hour,minute,second

#### trabajo con Strings:

- ltrim,rtrim, trim
- lpad,rpad
- lower,upper,initcap, reverse
- regexp

#### trabajo con colecciones:

- size, sort_array, array_contains, explode
- from_json, to_json
- when, coalesce, lit

#### User Defined Functions (UDF):

- pyspark udf funcions
- pandasUDF (vectorized udf)

#### Window Functions

- row_number, rank, dense_rank
- agg functions in window partitions
