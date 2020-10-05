# EJERCICIOS AUTOEVALUACION SEMANA 2

## Ejercicio 1

###Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años

El servidor escogido es del catalogo de la página pccomponentes y es el siguiente: ![Dell PowerEdge T340](https://www.pccomponentes.com/dell-poweredge-t340-intel-xeon-e-2124-8gb-1-tb) con un precio de 815,95€

Segun la ![tabla de la agencia tributaria de coeficientes de amortizacion](https://www.agenciatributaria.es/AEAT.internet/Inicio/_Segmentos_/Empresas_y_profesionales/Empresas/Impuesto_sobre_Sociedades/Periodos_impositivos_a_partir_de_1_1_2015/Base_imponible/Amortizacion/Tabla_de_coeficientes_de_amortizacion_lineal_.shtml) el porcentaje para Equipos para procesos de informacion es del 25%.

Por lo tanto el coste de amortización de dicho ordenador en un periodo de 4 años con un 25% sería de 203,9875€ anuales y para un periodo de 7 años con un 14,2857% seria de 116,517€ anuales.  

## Ejercicio 2

###Usando las tablas de precios de servicios de alojamiento en Internet “clásicos”, es decir, que ofrezcan Virtual Private Servers o servidores físicos, y de proveedores de servicios en la nube, comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa solo el 1% o el 10% del tiempo.

Utilizaremos por ejemplo el proveedor VPS ![OVHcloud](https://www.ovh.es/order/vps/?v=3#/vps/build?selection=~(range~'Essential~pricingMode~'degressivity12~flavor~'vps-essential-2-4-80~os~'ubuntu_20_04~datacenters~(GRA~1))) que con su plan Essential nos ofrece las siguientes características:
	1.Procesador --> 2 vCore
	2.Memoria RAM --> 4GB
	3.Almacenamiento --> 80GB SSD NVMe
	4.Ancho de banda público --> 500Mb/s

Con este proveedor y este plan tenemos un compromiso de permanencia de 12 meses y nos cuesta 9,20€ al mes. Haciendo calculos nos saldría a 0,0127€ la hora.

Como proveedor de servicios en la nube he escogido por ejemplo ![DigitalOcean](https://www.digitalocean.com/pricing/) que nos ofrece un plan con unas caracteristicas bastante similares como son las siguientes:
	1.Procesador --> 2 vCPUs
	2.Memoria RAM --> 4GB
	3.Almacenamiento --> 80GB 
	4.Transferencia --> 4TB

Con este proveedor y este plan nos cuesta 20€ al mes y 0,030$ la hora.

Como vemos el precio que nos supone a la hora es mas bajo el de VPS por lo tanto si solo lo vamos a utilizar un 1% o un 10% nos renta contratar el primer plan.

## Ejercicio 3

###En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?


Como podemos ver en la siguiente captura del archivo ![Cpu info](./image/cpuinfo.png) el procesador que tiene mi pc es un Intel(R) Core(TM) i5-8265U CPU @ 1.60GHz

Los flags que tenemos activados en cada uno de los procesadores son los siguientes ![Flags](./image/flags.png)

El resultado al ejecutar la orden en una maquina virtual es el siguiente:  ![Flags](./image/flagsVirtualBox.png) 

Las comprobaciones tanto en la Raspberry PI como en el movil no las puedo realizar ya que no tengo Raspberry y mi movil es un Iphone.

## Ejercicio 4

###Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios. Usar siempre que sea posible un hipervisor que sea software libre.

Como hipervisor ya tengo instalado VirtualBox que además es libre y para mi uno de los mas faciles, potentes e intuitivos. A continuación adjunto una captura de pantalla: ![Hipervisor](./image/hipervisor.png) 

## Ejercicio 5

###Darse de alta en una web que permita hacer pruebas con alguno de los sistemas de gestión de nube libres como los mencionados en los párrafos anteriores, aunque sea temporalmente. Si la prueba es menos de un mes, simplemente anotarlo y dejarlo para el mes de diciembre, más o menos.








