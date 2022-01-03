# uoc-tcvd-pr2
Práctica 2 de la asignatura Tipología y Ciclo de Vida de los Datos de la UOC

# Repositorio
- https://github.com/juusechec/uoc-tcvd-pr2

# Objetivo
- Aprender a aplicar los conocimientos adquiridos y su capacidad de resolución de
problemas en entornos nuevos o poco conocidos dentro de contextos más amplios o
multidisciplinares.
- Saber identificar los datos relevantes y los tratamientos necesarios (integración,
limpieza y validación) para llevar a cabo un proyecto analítico.
- Aprender a analizar los datos adecuadamente para abordar la información contenida en
los datos.
- Identificar la mejor representación de los resultados para aportar conclusiones sobre el
problema planteado en el proceso analítico.
- Actuar con los principios éticos y legales relacionados con la manipulación de datos en
función del ámbito de aplicación.
- Desarrollar las habilidades de aprendizaje que les permitan continuar estudiando de un
modo que tendrá que ser en gran medida autodirigido o autónomo.
- Desarrollar la capacidad de búsqueda, gestión y uso de información y recursos en el
ámbito de la ciencia de datos

# Dependencias
- python 3.8
- sklearn
- scikit-learn
- numpy
- seaborn
- matplotlib
- pandas
- scipy.stats
- patsy
- statsmodels
- scikit-plot

# Pasos para instalar
```sh
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

# Ejecutar
```sh
source venv/bin/activate
jupyter-notebook "M2.851_20211_Practica2.ipynb"
```

# Guardar nuevas dependencias
```sh
pip freeze > requirements.txt
```

# Integrantes
- Jorge Ulises Useche Cuellar ([@juusechec](https://github.com/juusechec))
- Cristian Alejandro Zamora Flores ([@chrisitan](https://github.com/chrisitan))

# Descripción de los ficheros
- [M2.851_20211_Practica2.ipynb](./M2.851_20211_Practica2.ipynb): Notebook de la práctica.
- [M2.851_20211_Practica2.pdf](./M2.851_20211_Practica2.pdf): Documento de la práctica en formato PDF.
- winequality-red.csv: Archivo de origen de los datos.
- winequality-red-sel.csv: Archivo resultante de la limpieza de los datos.
- .gitignore: Archivo que nos ayuda a decirle al sistema git qué queremos trackear en la gestión del versionamiento del código.
- LICENSE: Licencia del código generado, no de la información resultante o de las herramientas usadas.
- README.md: Documentación del proyecto.
- requirements.txt: Lista de las dependencias del proyecto python.

# Vídeo con la explicación
[![playvideo](https://user-images.githubusercontent.com/42657278/147869839-3896d204-8724-473d-b80c-26b41e0429fc.png)](https://drive.google.com/file/d/1bMuUvG7gFw1s-fqEA438U4YMWdsK6Lc0/view?usp=sharing)
