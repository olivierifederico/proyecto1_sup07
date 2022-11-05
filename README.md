<h1>Proyecto 01 - SUP07</h1>

![Netflix-Logo](_src\netflix-logo.png)

<h3>Limpieza de datos + Api + Extra</h3>

<h4>Consigna</h4>
<p>El trabajo consiste en hacer el proceso de limpieza de datos en python, crear una api que al conectarnos nos devuelva un diccionario con la tabla indicada </p>

- Ingestar datos del dataframe netflix.csv a python
- Cambiar el tipo de la columna date_added a datetime
- Ordenar de mas antiguo a mas reciente usando : ".sort_values(by=['date_added'])" 
- Reemplazar en la columna "director" el valor "Not Given" por None
- Usando mascaras dividir en 3 dataframes distintos, "release_year" 2019, 2020, 2021
- Transformar los 3 dataframes en 3 diccionarios distintos usando: .reset_index().to_dict(orient="index")
- Crear contenedor de Docker
- Crear una Api usando fastapi
- Crear 3 decoradores que devuelvan los distintos diccionarios
"/2019","/2020","/2021"
- Subirlo a Mogenius
---



<h4> Mini Guia Dockerfile </h4> 

+ Dockerfile 
+ FROM tiangolo/uvicorn-gunicorn-fastapi
+ RUN pip install pandas
+ Puerto 80
+ Copiar la carpeta de sus archivos dentro de Docker(El jueves lo vimos)

----
<h4>Mini Guia Mogenius</h4>

+ Crear cuenta
+ Create cloudspace (FREE)
+ Deploy a repository with Dockerfile
+ Linkear con la cuenta de GitHub
+ Poner nombre
+ Elegir repositorio
+ Poner todos los recursos a la mitad
+ Poner puerto 80 https
+ Crear servicio 

---
<h3>Tips</h3>

- Trabajen con GitHub desde el principio
- Vayan documentando cada parte
- No hagan trampa

<h2>Hay premio para el que lo complete </h2>
???


![meme](_src\PC180288.jpg)