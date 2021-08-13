## Listes des requête :
curl ```$ curl 'https://api.ipify.org?format=json'```

get/post ``` https://api.ovh.com/console/#/domain ```

## Environnement
```
                                       +--------------------+ 
+--------------------+                 |      WEB API       |
|      WEB API       |                 |    api.ovh.com     |  
|    www.ipify.org   |                 |   ZoneName Adress  | 
+--------------------+                 +--------------------+
         ^                                       ^      
         |                                       | 
       Fecth                                     PUT       
         |                                       |
         |                                       |
+--------------------+                           |      
|  SERVER ~ UBUNTU   |                           |
|   Nodejs projet    | --------------------------- 
|      Crontab       |
|    */60 * * * *    |
+--------------------+

```

## API pour le script :

```
https://www.ipify.org
https://api.ovh.com
```
