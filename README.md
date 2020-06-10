# SystemsDesign - Proxy with nginx 

Ein kleines Coding Beispiel, um die Response vom Server zu zeigen mit und ohne Proxy. Nginx wird hier als Reverse Proxy benutzt.


## Schritt 1
Navigiere im Terminal zum Ordner, tippe "node server.js"

## Schritt 2
curl localhost:3000/hello >> erwartete Response vom Server

## Schritt 3
curl localhost:8081/hello >> Header und host werden von nginx.conf vorgegeben
