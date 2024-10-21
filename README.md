Para usarlo escribe en la terminal : python3 main.py [nombre del archivo donde tienes el nombre de los dominios a los que quieres hacer peticiones] // (o python dependiendo de tu caso)
Este script tiene como propósito hacer una serie de peticiones get a los dominios que le pasemos por el archivo mediante el sys.args y mostrarnos el numero de respuesta de cada uno, todo esto ordenado en
un archivo que nos creara al ejecutarlo que se llamará resultados.txt . Esta importado en el main la funcion que definimos en el archivo input_handler para poder recibir parámetros por la terminal y asi indicar
cual es el archivo que vamos a usar, el domains.txt que esta en el repositorio esta como ejemplo por si lo quieres probar pero puedes usar cualquiera, este script añade el componente https a la url por default si no
lo tiene, asi que las paginas que no lo tengan darán error. En resumen, iterara el archivo que le demos y uno por uno hará una peticion get a cada uno mostrandonos su status_code, lo imprimira en el archivo resultados.txt
en mayúsculas y con su respectivo status_code.
