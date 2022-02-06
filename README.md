# SuccessPro

:::::::::::: IMPORTANTE ::::::::::::::::

El desglose del proyecto es el siguiente

en la raiz del repositorio se encontrara los siguientes directorios:


  1. Carpeta API PRUEBAS: contiene los archivos de la pruebas API al igual que informe de incidencias e informacion de como desplegar la prueba, 
     el contenido del directorio es el siguiente:
        
        a. ApiPrueba.jmx : este archivo es la prueba realizada en Jmeter sera el que se debera abrir dentro de la herramiente Jmeter
        
        b. Incidencias en prueba API.docx : Este archivo continen las incidencias encontradas en el proceso de pruebas de api
        
        c. Pasos para desplegar la prueba.txt : Este archivo contiene los pasos a realziar para desplegar la prueba y ejecutarla sin que se generen fallos en el proceso
        
        d. registros.csv : Este archivo contiene los datos de registro de usaurios que seran usadon en las pruebas parametrizadas de API, de alli se sustraen los 
           datos de registro de usuario
        
        NOTA: ES IMPORTANTE LEER LOS PASOS PARA DESPLEGAR LA PRUEBA
        
     
  2. Carpeta SuccesPro: Contiene los archivos y directorios que conforman el proceso de prueba manual y automatizadas de la web indicada, el contenido de este directorio es:
          
        a. automatizacion.py : archivo python que contiene el codigo de la prueba automatizada realizada al sistema web
        
        b. Casos de prueba.xlxs : Contiene los casos de pruebas manuales realizados al sistema web, en dicho archivo podran visualizar, los distintos escenarios a probar con                resultados esperados, resultados obtenidos y las incidencias encontradas en el proceso
        
        c. Cierre de Actividades.docs : archivo que contiene resumen del proceso de pruebas manuales y automatizadas indicando los pormenores del proceso de pruebas
        
        d. IMPORTANTE PARA CORRER AUTOMATIZACION.docs : Este archivo contiene paso a paso de lo que se debe configurar para ejecutar la prueba automatizada, es IMPORTANTE 
           Leer y realizar los pasos que se indican en este documento para relaizar la automatizacion
           
        e. recursos.zip : este comprimido .zip contiene una carpeta de recursos la cual cuenta con los datos de usuarios utilziados en el proceso de automatizacion, al igual que            el driver para ejecutar pruebas y la carpeta de screenshots de evidencia
        
        NOTA: ES IMPORTANTE LEE EL DOCUMENTO PARA CORRER PRUEBA DE AUTOMATIZACION YA QUE ALLI SE INDICAN LOS PASOS A SEGUIR PARA QUE LA AUTOMATIZACION FUNCIONE
  
  3. Carpeta Venv : Es la variable de entorno creada por python al momento de crear el proyecto
  
  
  4. Comunicaion de Bloqueante.docs : este archivo indica los problemas encontrados a los largo del proceso de desarrollo de pruebas, manbunales, automatizadas y de API que se        realizaron sobre el sistema web indicado 
