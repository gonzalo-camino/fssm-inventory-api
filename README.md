# fssm-inventory-api
Source code needed for Field DevOps Demo Exercise (FSSM)

## Create required DB objects
You can find the script to execute on the file `src/main/resources/db/script.sql`. It includes DDLs to create objects, plus asome inserts to generate data.

## Configure DB properties before running
In order to configure the DB connection, please edit the file `src/main/resources/conf/configuration.yaml`:
```
mysql:
  host: "<DB_HOSTNAME>"
  port: "<DB_PORT>"
  user: "<DB_USERNAME>"
  password: "<DB_PASSWORD>"
  database: "<DB_NAME>"
```

## API Spec (RAML)
If you want to inspect the API Spec of this API, please take a look to the file `src/main/resources/api/inventory-api.raml`

## Inspect the API console
Once running, you can access the API Console of this API going to this link: `http://localhost:8081/console`