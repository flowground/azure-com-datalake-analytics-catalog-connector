# ![LOGO](logo.png) DataLakeAnalyticsCatalogManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the DataLakeAnalyticsCatalogManagementClient API (version 2016-11-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/datalake-analytics-catalog/2016-11-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:58+03:00

## API Description

Creates an Azure Data Lake Analytics catalog client.

## Authorization

This API does not require authorization.

## Actions

### Retrieves the list of access control list (ACL) entries for the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of databases from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified database from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of access control list (ACL) entries for the database from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of assemblies from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the assembly.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified assembly from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the assembly.
* `assemblyName` - _required_ - The name of the assembly.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of credentials from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the schema.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified credential from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the schema.
* `credentialName` - _required_ - The name of the credential.
* `api-version` - _required_ - Client Api Version.

### Modifies the specified credential for use with external data sources in the specified database

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the credential.
* `credentialName` - _required_ - The name of the credential.
* `api-version` - _required_ - Client Api Version.

### Deletes the specified credential in the specified database

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the credential.
* `credentialName` - _required_ - The name of the credential to delete
* `cascade` - _optional_ - Indicates if the delete should be a cascading delete (which deletes all resources dependent on the credential as well as the credential) or not. If false will fail if there are any resources relying on the credential.
* `api-version` - _required_ - Client Api Version.

### Creates the specified credential for use with external data sources in the specified database.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database in which to create the credential. Note: This is NOT an external database name, but the name of an existing U-SQL database that should contain the new credential object.
* `credentialName` - _required_ - The name of the credential.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of external data sources from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the external data sources.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified external data source from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the external data source.
* `externalDataSourceName` - _required_ - The name of the external data source.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of schemas from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the schema.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified schema from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the schema.
* `schemaName` - _required_ - The name of the schema.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of packages from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the packages.
* `schemaName` - _required_ - The name of the schema containing the packages.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified package from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the package.
* `schemaName` - _required_ - The name of the schema containing the package.
* `packageName` - _required_ - The name of the package.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of procedures from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the procedures.
* `schemaName` - _required_ - The name of the schema containing the procedures.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified procedure from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the procedure.
* `schemaName` - _required_ - The name of the schema containing the procedure.
* `procedureName` - _required_ - The name of the procedure.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of all table statistics within the specified schema from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the statistics.
* `schemaName` - _required_ - The name of the schema containing the statistics.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of tables from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the tables.
* `schemaName` - _required_ - The name of the schema containing the tables.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `basic` - _optional_ - The basic switch indicates what level of information to return when listing tables. When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned. By default, it is false. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified table from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the table.
* `schemaName` - _required_ - The name of the schema containing the table.
* `tableName` - _required_ - The name of the table.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of table partitions from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the partitions.
* `schemaName` - _required_ - The name of the schema containing the partitions.
* `tableName` - _required_ - The name of the table containing the partitions.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified table partition from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the partition.
* `schemaName` - _required_ - The name of the schema containing the partition.
* `tableName` - _required_ - The name of the table containing the partition.
* `partitionName` - _required_ - The name of the table partition.
* `api-version` - _required_ - Client Api Version.

### Retrieves a preview set of rows in given partition.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the partition.
* `schemaName` - _required_ - The name of the schema containing the partition.
* `tableName` - _required_ - The name of the table containing the partition.
* `partitionName` - _required_ - The name of the table partition.
* `maxRows` - _optional_ - The maximum number of preview rows to be retrieved.Rows returned may be less than or equal to this number depending on row sizes and number of rows in the partition.
* `maxColumns` - _optional_ - The maximum number of columns to be retrieved.
* `api-version` - _required_ - Client Api Version.

### Retrieves a preview set of rows in given table.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the table.
* `schemaName` - _required_ - The name of the schema containing the table.
* `tableName` - _required_ - The name of the table.
* `maxRows` - _optional_ - The maximum number of preview rows to be retrieved. Rows returned may be less than or equal to this number depending on row sizes and number of rows in the table.
* `maxColumns` - _optional_ - The maximum number of columns to be retrieved.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of table statistics from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the statistics.
* `schemaName` - _required_ - The name of the schema containing the statistics.
* `tableName` - _required_ - The name of the table containing the statistics.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified table statistics from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the statistics.
* `schemaName` - _required_ - The name of the schema containing the statistics.
* `tableName` - _required_ - The name of the table containing the statistics.
* `statisticsName` - _required_ - The name of the table statistics.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of table fragments from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the table fragments.
* `schemaName` - _required_ - The name of the schema containing the table fragments.
* `tableName` - _required_ - The name of the table containing the table fragments.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of table types from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the table types.
* `schemaName` - _required_ - The name of the schema containing the table types.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified table type from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the table type.
* `schemaName` - _required_ - The name of the schema containing the table type.
* `tableTypeName` - _required_ - The name of the table type to retrieve.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of table valued functions from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the table valued functions.
* `schemaName` - _required_ - The name of the schema containing the table valued functions.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified table valued function from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the table valued function.
* `schemaName` - _required_ - The name of the schema containing the table valued function.
* `tableValuedFunctionName` - _required_ - The name of the tableValuedFunction.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of types within the specified database and schema from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the types.
* `schemaName` - _required_ - The name of the schema containing the types.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of views from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the views.
* `schemaName` - _required_ - The name of the schema containing the views.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the specified view from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the view.
* `schemaName` - _required_ - The name of the schema containing the view.
* `viewName` - _required_ - The name of the view.
* `api-version` - _required_ - Client Api Version.

### Deletes all secrets in the specified database. This is deprecated and will be removed in the next release. In the future, please only drop individual credentials using DeleteCredential

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the secret.
* `api-version` - _required_ - Client Api Version.

### Deletes the specified secret in the specified database. This is deprecated and will be removed in the next release. Please use DeleteCredential instead.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the secret.
* `secretName` - _required_ - The name of the secret to delete
* `api-version` - _required_ - Client Api Version.

### Gets the specified secret in the specified database. This is deprecated and will be removed in the next release. Please use GetCredential instead.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the secret.
* `secretName` - _required_ - The name of the secret to get
* `api-version` - _required_ - Client Api Version.

### Modifies the specified secret for use with external data sources in the specified database. This is deprecated and will be removed in the next release. Please use UpdateCredential instead.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the secret.
* `secretName` - _required_ - The name of the secret.
* `api-version` - _required_ - Client Api Version.

### Creates the specified secret for use with external data sources in the specified database. This is deprecated and will be removed in the next release. Please use CreateCredential instead.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database in which to create the secret.
* `secretName` - _required_ - The name of the secret.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of all statistics in a database from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the table statistics.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of all tables in a database from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the tables.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `basic` - _optional_ - The basic switch indicates what level of information to return when listing tables. When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned. By default, it is false
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of all table valued functions in a database from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the table valued functions.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Retrieves the list of all views in a database from the Data Lake Analytics catalog.

*Tags:* `Catalog`

#### Input Parameters
* `databaseName` - _required_ - The name of the database containing the views.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-datalake-analytics-catalog-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
