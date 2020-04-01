# Deteccion-de-accidentes-automovilisticos
![Alt text](https://github.com/juandmantilla/Deteccion-de-accidentes-automovilisticos/blob/master/Notebooks/banner%20Vision2-01.png "Banner Proyecto")

Proyecto de Visión por Computador para la detección de accidentes automovilísticos por medio de videos de CCTV reales y generados por el software de simulación BeamNG. Este proyecto está pensado hacia la problemática de accidentes de tránsito, ya que por medio de modelos de Deep Learning se podría alertar de manera temprana sistemas de urgencias. 

El proyecto consiste en la implementación de modelos pre entrenados, aplicando transfer learning para mejorar la precisión en la detección de accidentes. Los modelos usados son VGG16, MobileNet, Resnet 101 V2, Inception y XCeption. Además de estos modelos se potenció el modelo que tenía mayor tasa de acierto (Resnet), a este modelo se le aplicó transfer learning (entrenamiento de las últimas capas convolucionales) y adición de capas densas con activaciones LeakReLU (alpha = 0.3).

En este repositorio puede encontrar el dataset usado, cabe aclarar que estos datos son recolectados de videos de youtube. Los datos de accidentes son generados por el software de simulación de choques BeamNg como también de videos reales de accidentes.

Autor : Juan David Mantilla López
Contacto : juandmantilla@outlook.com

