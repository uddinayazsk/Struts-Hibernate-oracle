# Struts-Hibernate-oracle---The project is in DupMyProj
Anecdotes of the project---
Facade design pattern was used
User logs into the module using login page where struts call happens then using hibernate ORM user fetched data from oracle for username &
password.
If it's successful he will be getting one jsp for uploading a file (resticted bat or exe file) where he can upload file using struts framework again
While uploading no batch or exe file is allowed for security sake & duplicate prevention is implemented by struts. means if you submit or upload file once then same user will not be permitted once again to upload another file using struts, this can be achived.
