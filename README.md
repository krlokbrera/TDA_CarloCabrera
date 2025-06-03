#TDA_CarloCabrera
Este repositorio contiene el código desarrollado durante la realización del Trabajo de Fin de Grado del Grado en Ingeniería Informática de la Universidad Politécnica de Madrid, centrado en el análisis de trayectorias GPS mediante técnicas de Análisis Topológico de Datos (TDA).

📁 Estructura del repositorio
Archivo/Notebook	Descripción
Diagrams_Geolife.ipynb	Script principal para la carga, visualización y análisis topológico de trayectorias GPS del dataset Geolife mediante homología persistente.
Clustering.ipynb	Experimentos de comparación utilizando técnicas tradicionales como clustering (k-means, DBSCAN) y PCA sobre los datos vectorizados.
Plantilla_TDA_Trayectorias.ipynb	Notebook organizado como plantilla reproducible para análisis topológico con distintos datasets y configuraciones.

📊 Dataset utilizado
Se utiliza el conjunto de datos Geolife GPS Trajectories, que contiene miles de trayectorias recogidas por usuarios en dispositivos GPS. Cada archivo .plt incluye coordenadas geográficas (latitud, longitud) con marcas temporales y altitud.

🧠 Tecnologías y bibliotecas
Python 3.11

Giotto-TDA 🌀

Scikit-learn

Numpy / Pandas

Matplotlib / Seaborn / Plotly

⚙️ Requisitos
Instala los paquetes necesarios ejecutando:

bash
Copiar
Editar
pip install -r requirements.txt
Si no tienes un requirements.txt, puedes instalar manualmente:

bash
Copiar
Editar
pip install gtda numpy pandas matplotlib scikit-learn seaborn plotly shapely
🚀 ¿Qué puedes hacer con este código?
Visualizar trayectorias en 2D y 3D.

Calcular diagramas de persistencia con Vietoris-Rips.

Aplicar PCA a las trayectorias para análisis comparativo.

Utilizar Mapper para obtener representaciones topológicas globales.

Comparar métodos tradicionales (clustering, reducción de dimensión) con métodos TDA.

📌 Objetivo del proyecto
Demostrar cómo el análisis topológico de datos puede complementar y mejorar la interpretación de trayectorias GPS frente a métodos tradicionales, aplicando técnicas como:

Homología persistente

Mapper

Imágenes de persistencia

Comparación con clustering clásico, PCA y otras técnicas estadísticas

📚 Licencia
Repositorio académico con fines educativos. Todos los derechos reservados por el autor.
