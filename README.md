# AWS-PostgreSQL-RDS-Table-Partition
AWS PostgreSQL RDS Table Partition

Its just sample script for partition , you can use this as reference and perform same operation for your table

Validate each partition :
-------------------------

select * from datablogspaycheck_202303 order by 2 desc

select * from datablogspaycheck_20230304 order by 2 desc

select * from datablogspaycheck_202311 order by 2 desc
