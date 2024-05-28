# openmaint-docker

### Deploy by docker run
**openMAINT with demo database**  

```bash
docker-compose -f openmaint-2.3-3.4.3/docker-compose.yml up -d
```  

#### CMDBUILD_DUMP values
* demo.dump.xz
* empty.dump.xz

#### Please change credentials for postgres and tomcat server
* @ openmaint-2.3-3.4.1-d/docker-compose.yml - idealy using enviroment variables
* @ openmaint-2.3-3.4.1-d/files/context.xml
* @ openmaint-2.3-3.4.1-d/files/tomcat-users.xml
#### Credentials and access to OM
* **Link to OM** - http://localhost:8090/cmdbuild/ui/
* **username** - admin (default)
* **password** - admin (default)
