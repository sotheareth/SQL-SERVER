# SQL-SERVER

SELECT getdate() , dateadd(dd, datediff(dd, 0, getdate()), 0)

SELECT DATEADD(ms, -3, dateadd(dd, datediff(dd, 0, getdate()), 1))


2017-05-06 15:40:40.353	      2017-05-06 00:00:00.000

2017-05-06 23:59:59.997
