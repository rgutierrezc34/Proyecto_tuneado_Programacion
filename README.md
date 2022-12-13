![image](https://user-images.githubusercontent.com/119511322/207469564-007f5b3a-1fb3-4330-ad79-778fa973c16d.png)

**Determinación de volúmenes de caudales  y su ubicacion en python**

Autor del proycto: Reyes Omar Gutierrez Camacho

Institución: Facultad de Ingeniería Civil, Universidad de Colima, Campus Coquimatlán

Carrera: Ingeniero Topógrafo Geomático

Grado y grupo: 3ºB

Profesor Titular: Sebastián González Zepeda

Lugar: Campus Coquimatlán; Coquimatlán, Colima

Fecha: 12 de diciembre 2022

**Resumen**

Se generará un programa en Python el cual tiene como propósito leer un archivo de Excel, en el que se encuentran datos de un levantamiento de secciones sobre un canal que se encuentra en el campus Coquimatlán en la Facultad de Ingeniería Civil, para obtener como resultado que el programa genere de manera automática el volumen obtenido de cierto canal proporcionándole ciertos datos clave, también para un mayor entendimiento visual graficar los resultados.

**Palabras clave**: 1. Programa. 2.Python. 3. Canales



**Abstract**

A Python program will be generated whose purpose is to read an Excel file, in which data from a survey of sections on a canal located on the Coquimatlán campus in the Faculty of Civil Engineering are found, to obtain as a result that the program automatically generates the volume obtained from a certain channel, providing you with certain key data, also for a better visual understanding, graph the results.


**Keywords**: 1. Program 2. Python 3. Channels.


## **Introducción**

El presente informe se hablara del cálculo de volúmenes apoyándose de la área de geolocalización por medio del uso de Python y Google Colab, así como se pretende la elaboración de un código en lenguaje Python que nos sea de ayuda para realizar cálculos sobre volúmenes, velocidad del agua por segundo en los canales así como la graficacion de una sección en particular del canal, con el uso de distintas bases de la programación lograr que nuestro código Python pueda mostrarnos la localización del canal mediante el uso de distintas librerías, además poder identificar si la pendiente es positiva o negativa, como elemento un poco más enfocado a lo geoespacial se tiene planeado realizar un apartado en el código que nos permita que mediante las coordenadas del lugar nos arroje la ubicación del canal en donde se realizó el trabajo. 

Dicho todo esto, daremos inicio al informe comenzando con el desarrollo de este proyecto.
  
## **Desarrollo**

Primeramente, antes de comenzar la realización de los programas y mostrar el resultado final, se realizan diversas investigaciones en las cuales se tiene como objetivo tener una idea más clara de cuál será el proceso que se deberá seguir para que nuestros códigos de Python sean lo suficientemente satisfactorio.

Hay que destacar que este proyecto tiene gran importancia, ya que se va a evaluar la calidad del producto de una serie de procedimientos que se realizaron para poder así llevarlo a cabo y los resultados que se obtendrán sean favorables. 

Los datos sobre la sección en especifico se toman de una practica topográfica la cual consistía en el levantamiento de secciones transversales justamente de un caudal de interés dentro de las instalaciones de la facultad, con esto obtuvimos los datos mas relevantes y de importancia para la realización de este proyecto final. 

Algunas de las herramientas / materiales que utilizamos y fueron fundamentales necesitan para poder llevar a cabo este proyecto final son:

- Nivel de mano
- Estadales
- Longimetro
- Python
- Google Colab.
- Excel

Posterior a esto se procede a investigar a que tipo de canal pertenece el canal en el que realizamos el estudio, esto para saber como calcular el volumen y hacer que nuestros datos sean los necesarios para realizar esos cálculos correspondientes en Python.

Se comienza la investigación sobre librerías de Python que se puedan utilizar para poder darnos la ubicación del área de estudio, esto va enfocado mas a lo geoespacial, entre estas librerías se encuentran Basemap, Folium, entre otras, las cuales nos pueden marcar mediante un punto donde se encuentra el lugar de trabajo.









1. Exportamos los datos obtenidos de las secciones a una hoja de cálculo en Excel, para tener un mejor manejo de los datos.

![](Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.002.png)

*Imagen 1. Datos del canal.*

2. Subimos nuestro archivo Excel a nuestro drive y procedemos a crear el código que nos permitirá graficar la sección de dicho canal ya mencionado, al código tenemos que ponerle el nombre del archivo que subimos a drive y ejecutara los datos de las secciones.

![](Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.003.png)

*Imagen 2. Código grafico de secciones con el uso de la librería matplotlib.*

3. Ejecutamos y nos dará el resultado de la sección referida de dicho canal graficada con el uso de las librerías.

![](Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.004.png)

*Imagen 3. Resultado grafico obtenido del código grafico de secciones.*




4. Además, este programa nos permitirá conocer dicha ubicación del canal ubicado en la 	Facultad de Ingeniería Civil. 

![](Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.005.png)

*Imagen 4. Código Python geoespacial.*


La ejecución del código mostro lo siguiente:

![](Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.006.png)

*Imagen 5. Código ejecutado resultado con el uso de las librerías matplotlib y basemap.*

Para el cálculo del volumen del canal en Python realizamos un código que a partir de las características del canal nos permitiera conocer cuál sería su volumen.


5. Ya como último paso que realizamos fue crear el programa en Python para poder calcular el volumen (caudal) de dicho canal con los datos obtenidos, para realizar el código tomamos en cuenta las características de los canales y ciertos aspectos que nos parecieron interesantes para poder conocer el volumen (caudal), a partir de ciertos datos a ingresar de forma manual al programa. otra parte interesante que tiene el código de programación es que se pueden integrar los datos de manera manual, para poder así tener el manejo de los datos. 

![](Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.007.png)*Imagen 6. Código Python Volumen canal*

Resultado obtenido después de la ejecución: 

![](Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.008.png)

*Imagen 7. Resultado código ejecutado cálculo de volúmenes*

6.Se realizo también dos códigos en colab los cuales también van de entrada en nuestra parte geoespacial del proyecto realizado, el primer código realizado nos permite obtener la ubicación del lugar de estudio en un mapa interactivo implementando la librería folium.

(Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.009.png)



`         `*Imagen 8. Resultado mapa interactivo con folium.*

Posteriormente se realizó un programa que, mediante las coordenadas del lugar, este te 
arrogara datos relevantes del sitio, por ejemplo, la calle, código postal, ciudad, etc.
## **3. Manejo de datos**
Las librerías utilizadas para realizar los códigos correspondientes utilizando el lenguaje Python de este proyecto son las siguientes:

- Numpy: La librería NumPy nos permitió una generación y manejo de datos extremadamente rápido. NumPy tiene su propia estructura de datos incorporada llamado arreglo que es similar a la lista normal de Python, pero puede almacenar y operar con datos de manera mucho más eficiente.
- ![](Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.010.png)Matplotlib: Esta librería nos ayudo a realizar el grafico de las secciones del canal. Matplotlib es una librería de Python especializada en la creación de gráficos en dos dimensiones. Permite crear y personalizar los tipos de gráficos más comunes, entre ellos: Diagramas de barras.

*Imagen 9. Código ejecutado resultado con el uso de las librerías matplotlib.*

- Basemap: Basemap no es exactamente una librería como tal. De hecho, es un conjunto de herramientas, una extensión, de la propia librería Matplotlib de Python.

Esta librería nos fue de gran ayuda ya que nos permitió por medio del código obtener como resultado el mapa con la ubicación de dicho canal.

![](Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.011.png)

*Imagen 10. Resultado con el uso de las librerías basemap.*

- Folium: Librería que se utiliza para visualizar los mapas y el manejo mediante el uso de Python.
- Geopandas: GeoPandas es una de las librerías geoespaciales más completas de Python. Podríamos decir que es sencilla a la vez que compleja. 

Esta librería nos ayudo a obtener la ubicación geoespacial del canal, ubicado en la Facultad de Ingeniería Civil.

![](Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.012.png)

*Imagen ilustrativa 11. Resultado con el uso de las librerías Geopandas.*

- GeoPy: GeoPy facilita a desarrolladores de Python localizar las coordenadas de direcciones, ciudades, países y puntos de referencia en todo el mundo mediante geocodificadores de terceros y otras fuentes de datos.

La librería nos ayudó a localizar la ubicación del canal. ![](Aspose.Words.9232ef8e-3592-46eb-8b22-b0523646c43f.013.png)

*Imagen 12. Resultado con el uso de las librerías GeoPy.*

El uso de estas librerías fue esencial para el manejo de los datos en Python.

Como recomendación, para la graficacion de la sección del canal sugerimos que al utilizar el programa realizado por nosotros se debe de tener antes muy bien ordenada la información de nuestro dataframe (Excel) pues solo se podrá ejecutar de la manera correcta si se cuenta con la información ordenada en columnas y cada una de ellas con los nombres correspondientes (Cadenamientos) y (Cotas).
## **4. Resultados**
Respecto a los resultados, podemos decir que, si se lograron cumplir con los objetivos que nos planteamos para la elaboración de nuestro programa de Python, es decir, se pudo programar y obtener el volumen de dicho canal, se logro graficar las secciones del canal, además de poder geolocalizar el canal por medio de librerías geoespaciales en donde se especifica a detalle la ubicación y las coordenadas de este mismo.

Conforme al procesos del desarrollo de los programas pudimos comprobar que los datos obtenidos eran correctos tanto para el cálculo del volumen del canal y el grafico de las secciones del canal, además el uso de estas librerías nos sirvió de mucha ayuda de acuerdo con el objetivo del proyecto.

Los códigos realizados fueron los siguientes: 

#Codigo para cálculo de volumen Canal.

# Datos de entrada

base = float(input("Base(m) : "))

z = float(float (input("Z : ")))

S = float(input("pendiente de fondo S: "))

n = float(input("rugorosidad : "))

y = float(input("tirante normal (m) : "))

# Cálculos 

A = base\*y+z\*y\*\*2

P = base+2\*y\*(1+z\*\*2)\*\*.5

R = round(A/P,2)

print('El radio hidráulico es (m) : ', R)

#Velocidad

V = round(1/(n)\*R\*\*(2/3)\*S\*\*.5,2)

print('La velocidad del agua es de (m/s) :', V)

Q = round(V\*A,2)

print('El volumen es de (m3):',Q)

# Código para graficar las secciones.

from google.colab import files

from google.colab import drive

import matplotlib.pyplot as plt

import pandas as pd

import xlrd

drive.mount('/gdrive')

df= pd.read\_excel('/gdrive/MyDrive/Colab Notebooks/SECCIONES/SECCIONES.xlsx',sheet\_name= 'Hoja1')

VALORES = df[['Cadenamientos','Cotas']]

ax= VALORES.plot(x='Cadenamientos', y= 'Cotas',rot=0)

plt.xlabel('Cadenamientos')

plt.ylabel('Cotas')

plt.show


# Código para obtener la ubicación mediante las coordenadas.

from geopy.geocoders import Nominatim

geolocalizador = Nominatim()

ubicacion = geolocalizador.reverse("19.211186523699826, -103.80443942468253")

print(ubicacion.address)

print(ubicacion.latitude, ubicacion.longitude)

print(ubicacion.raw)

# Código Geoespacial para obtener la ubicación.

%matplotlib inline

import numpy as np

import matplotlib.pyplot as plt

from mpl\_toolkits.basemap import  Basemap

fig = plt.figure(figsize=(8, 8))

m = Basemap(projection='ortho', resolution=None,

`            `width=8E6, height=8E6, 

`            `lat\_0=45, lon\_0=-100,)

m.etopo(scale=1.0, alpha=1.0)

# Map (long, lat) to (x, y) for plotting

x, y = m(-103.80450468775071,19.21095061186164)

plt.plot(x, y, 'ok', markersize=5)

plt.text(x, y, ' Caudal\_FIC', font size=22);

#Codigo para un mapa interactivo en la ubicacion del lugar

import folium

m = folium.Map( 

`    `location=[19.211249641928656, -103.80451631674501], 

`    `zoom\_start=12, 

`    `tiles='Stamen Terrain' 

) 

tooltip = 'Canal de estudio'

folium.Marker([19.211249641928656, -103.80451631674501], popup='Canal de estudio', tooltip=tooltip).add\_to(m) 

## **5. Conclusiones**
A modo de cierre de este proyecto es importante mencionar que la intención de realizarlo era poder hacer un programa en Python, el cual nos calculara el volumen del canal, graficara las secciones y pudiera geolocalizar el lugar donde se ubica dicho canal. El cual logramos cumplir nuestros objetivos puestos para este proyecto. 

Al ser un éxito este programa, podemos usarlo como una gran herramienta de suma importancia para nosotros estudiantes, futuros ingenieros, y nos servirá de mucho al realizar los cálculos (volúmenes, secciones, ubicación) de un canal de una manera más rápida y sencilla.

Por ello, no cabe duda alguna que la programación juega un papel muy útil en la vida humana, y en las ingenierías no es la excepción, pues con ella podemos realizar varios procesos u las cuales manualmente no tomaría bastante tiempo realizarlas, por lo que con el uso de programas informáticos podemos implementar y ejecutar de manera más rápida, precisa y eficaz, tal y como se pudo demostrar en este proyecto.

Para finalizar, el realizar este código nos deja una gran enseñanza, pues ejemplifica cómo es que podemos emplear la programación o los lenguajes de programación para resolver cuestiones de la vida diaria de cualquier tipo, principalmente enfocados en el área académica.

## **Referencias**
- Cordova, P. L. A. (2018, 13 marzo). AREAS Y VOLUMENES DE FIGURAS EN PYTHON.
- 6 formas de calcular el volumen. (2019, 13 marzo).
- <https://www.fao.org/fishery/docs/CDrom/FAO_Traning/FAO_Training/General/x6708s/x6708s08.htm>
- Estructuras en Canales. (2003, 31 agosto). oocities.
- El paquete Numpy — Fundamentos de Programación en Python. (s. f.). 
- Gonzalez, L. (2022, 23 septiembre). Introducción a la Librería Matplotlib de Python. Aprende IA. 
- Estévez, R. (2019, 9 agosto). Creando mapas con Python, Matplotlib y Basemap. geomapik.
- Rédac, T. (2022, 2 agosto). Folium: descubra la biblioteca de Python Open Source. Formation Data Science | DataScientest.com.
- Morales, A. (2021, 25 noviembre). GeoPandas: Análisis de datos geográficos en Python. MappingGIS. 
- Morales, A. (2021, 25 noviembre). GeoPandas: Análisis de datos geográficos en Python. MappingGIS


