# Log analytics

Es importante saber quién, cómo y desde dónde están entrando a nuestras webs. Por eso hemos desarrollado Log analytics, que es una aplicación de servidor, que coge los logs de Apache2, y los transforma a gráficas, para que lo podamos entender de la mejor forma posible. Cuenta con una base de datos de países para mostrar exactamente de qué país se está produciendo la conexión.

Las gráficas las genera un archivo de python, las separa por los distintos virtualhosts, y después se muestran en la web https://log-analytics.hectorgv00.online/ que está realizada con PHP con HTML embebido,, css y javascript.
