BluePrint
=========

Uses
----

* Postgresql
* JQuery
* SCSS
* Bootstrap
* Minitest
* Factory Girl
* Unicorn
* Figaro for environment variables

Any of these can be changed pretty easily.

Usage
-----

Clone to folder with name you choose for project
```
git clone git@github.com:nwalkingshaw/blueprint.git [FOLDER_NAME]
```

Change config/database.yml file
```
rake db:create:all  
```

Generate file for figaro
```
rails g figaro:install
```

Rename app using the included generator
```
rails g print new_app_name
```


### Customize!!
