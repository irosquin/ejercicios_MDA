# Nifi_ETL

1. Exploración de los datos de la API 

https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9

2. Levantamos un docker con Nifi, ElasticSearch y Kibana, que nos permita hacer la descarga de los datos de la API, llevarlos a Elasticsearch y pintarlos sobre un mapa

3. Nifi: 3 conectores
   - invokehttp : configuración para la descarga de los datos de data.cityofnewyork
   - splitJson
   - putElasticsearch: enviar los datos de data.ciyofnewyork a elasticsearch, creando un índice llamado nyc.
 
4. 
   
