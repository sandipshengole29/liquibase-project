# liquibase-project
This project contains the liquibase demo to maintain the application database changes.


DEPLOY THIS APPLICATION:

To deploy this application from STS use following command:
liquibase:update

deploy this application from command prompt use following command:
mvn liquibase:update

Rollback DB changes deployed using liquibase:
liquibase:rollback
liquibase:rollback -> liquibase.rollbackCount=10


Rollback DB changes deployed using liquibase from command prompt:
mvn liquibase:rollback
liquibase:rollback -> liquibase.rollbackCount=10
