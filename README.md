# Smarthome-Controller
1. Identify the problem domain  :


Temperatursensorerer til at opretholde stuetemperatur i huset. (slås fra hvis vindue er åbent)

Støvsugerrobotter (går i gang når jeg smutter hjemmefra)  

Wifi-controlled kaffemaskine (Kan brygge fra en app)  

Klappe-sensor til lys (tænd & sluk)   



3. Design your classes

KaffeMaskineApp.java ( Appen som styrer kaffemaskinen ) 

Støvsugerrobot.java (boolean CheckIfHome)

klappe-sensor (CheckIfClaps)

Sensor klasse - til at registrere når man klapper, til at registrere om der er nogle hjemme. 
Og til at registrere hvad temperaturen er.

abstractions, sensor klassen kan genbruges til alle sensorerne. 
Vi kan lave et interface til sensorerne der checker hvad temperaturen er i alle rum. 
