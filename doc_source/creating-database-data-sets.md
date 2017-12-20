# Creating Data Sets from New Database Data Sources<a name="creating-database-data-sets"></a>

You can use a variety of database data sources to provide data to Amazon QuickSight\. This includes Amazon RDS instances and Amazon Redshift clusters, and also MariaDB, Microsoft SQL Server, MySQL, and PostgreSQL instances in your organization, in Amazon EC2, or similar environments\.

When creating a new database data set, you can select one table, join several tables, or create a SQL query to retrieve the data that you want\. You can also change whether the data set uses a direct query or stores data in SPICE\.

When you create a data set based on an AWS resource like Amazon RDS, Amazon Redshift, or Amazon EC2, data transfer charges might apply when consuming data from that source\. Those charges might also vary depending on whether that AWS resource is in the home region you chose for your Amazon QuickSight account\. Refer to the pricing page for the service in question for more details on applicable pricing\.


+ [Required Permissions for Database Credentials](required-permissions.md)
+ [Network and Database Configuration Requirements](configure-access.md)
+ [Creating a Database Data Set](create-a-database-data-set.md)