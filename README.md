
# <h1 align=center>**Telecomunication_PI**</h1>

## Proyecto Data Analyst

-----

Introducción: 

La empresa **FuturaFibra**  - *prooveedora de servicios de internet*- piensa realizar una campaña de marketing enfocado en internet por fibra óptica para el año 2022. Desde la gerencia nos solicitan realizar un análisis completo que permita reconocer el comportamiento del sector a nivel nacional. 


Objetivos:

Dentro de los objetivos se nos solicita cumplir con los siguientes KPIS:

1 - Reducir la inversión de publicidad identificando las provincias de menor cobertura Y seleccionar aquella provincia que tiene mayor  cantidad clientes. para luego enfocarse en que localidades tenemos mayor cobertura. 

2 - Determinar si los ingresos por fibra optica en los trimestres 3 y 4 del  2022 superarán un 10% a los ingresos generados en los mismos trimestres pero del año 2021.

3 - Aumentar en un 20% o más las conexiones por fibra óptica para el 2022

-----


### <center>  **Contenido del Repositorio**

* Carpeta CSVS provistos por ENACOM con las metricas históricas de internet(usados para el EDA y el Dashboard)
 
* Archivo telecomunicaciones_OK de POWER BI donde se desarrolla el dashboard. 
* Archivo Jupiter llamado EDA.ipynb donde se realizó el EDA del proyecto
 
-------

----
### DESARROLLO A NIVEL NACIONAL DE TECNOLOGIAS DE CONECTIVIDAD A INTERNET

**Para esto se van a tomar los datos recopilados por el Ente Nacional de Comunicaciones(ENACOM). De los que la información cubre desde el año 2014 al primer trimestre del 2022**

<img src="https://user-images.githubusercontent.com/60153579/253780505-4f258747-cee1-4550-8bfe-8fd068c68870.JPG"> 

**La conexión a internet por fibra óptica aumentó a partir del año 2019 con una tendencia alsista, ocupando el segundo lugar en el 2022, ocupando el segundo lugar con un 21.39% del total de conectividad nacional.**


#  Total de ingresos Anuales. 

<img src="https://user-images.githubusercontent.com/60153579/253781357-050fe9f2-ca90-41f3-ac45-9c8a70e26cbd.JPG"> 

<img src="https://user-images.githubusercontent.com/60153579/253781355-28f6a4fe-2616-46b0-b8dd-b56519c11bd4.JPG">

### Para el primer trimestre de 2022 los ingresos nacionales por fibra óptica ocupan el segundo lugar con un total acumulado de $ 11.001.496

----


<img src="https://user-images.githubusercontent.com/60153579/253782664-b5b73b7b-77cb-46f5-96bc-9765a6c3caeb.JPG">

**Podemos apreciar que la mayor parte de los ingresos es por cable modem, luego ADSL y Fibra Optica con óptimo crecimiento.**

<img src="https://user-images.githubusercontent.com/60153579/253782663-e8a1b963-a10e-4504-b14c-b5418f78ca8c.JPG">


Ingresos expresados en miles generados por Fibra Óptica por trimestre.

<img src="https://user-images.githubusercontent.com/60153579/253818946-b2c1da46-2477-4a96-890e-c16b73d29b26.png">

<img src="https://user-images.githubusercontent.com/60153579/253818970-308a77e3-c7ef-4fbc-af87-4c8353565790.JPG">


-----

### Distribución de conexión a nivel nacional por tipo.
### Año 2020

<img src="https://user-images.githubusercontent.com/60153579/253782822-72a8048d-3b68-44f0-a12f-f24b43a6e1d3.JPG">

### Año 2021

<img src="https://user-images.githubusercontent.com/60153579/253782823-6eca045f-979a-4d88-b9b9-33642a2c4ed8.png">

## Desarrollo de conectividad historica de fibra óptica.


----


<img src="https://user-images.githubusercontent.com/60153579/253782824-2c64e343-3fd5-482a-8ed4-d2a19f43f987.png">

**La conexión por FO a crecido abruptamente a partir del año 2019**

----

---

**En Conclusión el desarrollo historico a nivel país de fibra óptica tuvo un activo desarrollo a partir del año 2019, llegando al primer trimestre de 2022 a cubrir casi la misma cantidad de clientes que en todo el año 2019. Por eso se espera que este desarrollo continue hasta llegar a 8.500.00 clientes**






------

# Conexión a Fibra óptica por provincia año 2021

<img src="https://user-images.githubusercontent.com/60153579/253782966-9aa25a88-470a-49c8-acc1-9a4fbce40bbc.png">

**La provincia de Buenos Aires se mantiene en el primer lugar en 2021 con 3.737.407 conexiones de fibra óptica. Más del 50% del total de conexiones a nivel país. La capital federal que se encontraba en segundo lugar en el 2019 con 128.797 conexiones, fué bajando producto del crecimiento de las provincias de Córdoba, Santa Fe, Tucuman y Mendoza.**

<img src="https://user-images.githubusercontent.com/60153579/253783277-e3735c87-adc1-47a7-ad56-91ee7c5b3f86.png">

#### Del año 2018 al año 2019 hay una duplicación de clientes conectados a fibra óptica. Producto de la inversión en el desarrollo de nuevos Km de tendido y de campañas publicitarias. Bs As pasa de tener 730.038 clientes conectados con fibra óptica a 1.813.913 clientes en el año 2019. Duplicó rapidamente su conectividad en fibra óptica. Su punto máximo de clientes se encuentra en el año 2021 con un total de 3.737.407

## Desarrollo histórico de fibra óptica en Córdoba
----

<img src="https://user-images.githubusercontent.com/60153579/253783331-15897b53-460f-4d40-8804-a5906409a3e3.png">

Del año 2018 al año 2019 hay un gran salto. Producto de la inversión en el desarrollo de nuevos Km de tendido de 
Fibra Óptica. Cordoba pasa de tener 60.470 clientes conectados con fibra óptica a 126.324 clientes en el año 2019. Duplicó rapidamente también su conectividad cómo Bs As. Su punto máximo de clientes se encuentra en el año 2021 con un total de 671.198. Está muy por debajo de lo que es Bs As.


Conclusiones:  
Teniendo en cuenta que en el año 2020 hubo una pandemia que paralizó al mundo. Los ingresos se vieron afectados y quedaron estancados. 
por eso no se va a tomar en cuenta ese año para realizar las proyecciones. 

1- Se identificaron las provincias con menor desarrollo de fibra óptica y se determinó que la próxima campaña publicitaria va a estar enfocada para la Provincia de Bs As.

2 - En el primer trimestre de 2022 se generaron ingresos por $ 1.764.424,29. Teniendo como referencia que en el primer trimestre de 2021 se generaron $ 587.431,91, ya estaríamos superando un 150% esa relación. El promedio de ingresos para los trimestres del año 2021 y el primer timestre de 2022 es de $ 1.229.878,53. Por lo que se espera obtner un total de $ 5 millones de pesos de ingresos para el año 2022

3 para el primer trimestre de 2022 se registran un total de 2.219.533 conexiones. Por lo que se estima llegar tener 8.000.000 de conexiones totales para todo el año 2022. Sería aproximadamente un 30% mas de los que hubo en el 2021.1 (6.473.506)
