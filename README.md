
# Directorio de trabajo para proyectos de ciencia de datos

### Descripción de las carpetas

- **data:** todos los datos que entran y salen
- **code:** código fuente
- **reports:** todos los productos entregables (gráficos, tablas, informes, etc.)
- **notebooks:** notebooks de prueba que se utilicen en el proceso
- **scripts:** código que automatiza tareas. Refiere a rutinas que que en general ejecutan el código que está dentro de code.
- **docs:** documentos de textos que tengan relación con el proyecto (papers, manuales, etc.)
- **models:** contiene los archivos de los modelos entrenados. Pueden ser modelos, tokenizadores, archivos de Huggingface, etc. 
- **config:** para los proyectos más complejos se incluye una carpeta de configuración, para manejar el comportamiento del código fuente

Varios directorios cuentan con un subdirectorio llamado *old*, en el cual es posible guardar archivos antiguos que ya no se estén usando.  


```
project
├──  README.md
│
└───data
│   ├── input/
|   ├── process/
|   ├── old/
│   └── output/
│    
└───code
|   ├── __init__.py
|   ├── algo.py
|   ├── algo.py
|   └── old/
|
└───reports
│   ├── plots/
|   ├── tables/
|   ├── old/
│   └── otros/
|
├───notebooks
|   └── old/
|
├───scripts/
|
├─── docs/
|
└───models/
|    └── old/
|
├─── config/
|
├───main.py / _targets.R   
|
├───docker-compose.yml
|
└───dockerfile.yml

```
