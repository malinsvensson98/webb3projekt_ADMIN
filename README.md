# Administration 
Länk till administration: https://malinsvensson.se/miun/webbutveckling3/projekt/src/login.php?message=

## Login.php
Med hjälp av lösenord och användarnamn så kan besökaren på denna webbplats komma in i administrationsgränssnittet. 
Vid fel lösenord visas ett felmeddelande och vid rätt lösenord skickas besökaren vidare till admin.

## Admin.php
Startsidan för administration. 
Besökaren kan härifrån gå in på tre undermenyer beroende på vilken tabell i databasen som ska justeras. 
Denna startsida innehåller även en "logga-ut-knapp". 

## CoursesSite.php, webSite.php, workSite.php
Undersidorna för administration med följande funktioner: 
- coursesSite: kurser läses ut och kan uppdateras samt raderas plus att besökaren härifrån kan lägga till nya kurser i databasen. 
- workSite: arbeten läses ut, med samma CRUD-funktioner som coursesSite.
- webSite: webbplatser läses ut, med samma CRUD-funktioner som övriga två.

## Logout.php
Loggar ut användaren och skickar sedan besökaren vidare till login.php. 

## Includes 
Innehåller header och footer som länkas in i de olika filerna.

