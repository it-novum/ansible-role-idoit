# Ansible Role - Configure idoit

#### Variables

* idoit_database_data: Name of the data database of the first mandator (default: idoit_data)
* idoit_database_system: Name of the system database (default: idoit_system)
* idoit_database_user: Name of the database user (default: idoit)
* vhost_user: The user under which the vhost runs (default: idoit)
* idoit_default_mandator: Name of the first mandator (default: itnovum)
* idoit_zip_file: Local path to the idoit installation file (default: idoit.zip)

#### Required files

If you want to install idoit with this role you have to put the current idoit installation zip to your local directory. The default path is
```bash
$PWD/idoit.zip
```
but this may be changed with the variable idoit_zip_file.
