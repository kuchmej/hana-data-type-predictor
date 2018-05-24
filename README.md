# hana-data-type-predictor


use maven to build the hana data type predictor code

Pass test skip flag in case if you need to skip Test case execution during install phase

mvn clean install -Dmaven.test.skip=true

# Schema Crawler தேனீ

Following parameters need to be passed as argument to the schema crawler 
Pass HANADB_HOST as system level environment variable

```
--task schema_crawler_master --src_dbo_name "DataLake.Deltaviews.TransactionViews/InstallationOwnershipTS" \
--output /tmp --write_mode csv --analytic_type hana \
--mdbenv development_mysql --mdbservice service local 
```


##### SIGN: NAGA JAY
