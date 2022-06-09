# D9 project to demo with drupal9ci

## Run project

### First time

```
git clone https://github.com/fjgarlin/d9.git d9
cd d9
mkdir web/sites/default/files
ddev start
ddev drush sql-cli < ./dump.sql
ddev drush uli
```

### Run local server

```
ddev start
ddev drush uli
```

## DB dump

Use this URL to set up CI:
* `DB_DUMP`: `https://raw.githubusercontent.com/fjgarlin/d9/main/dump.sql`
