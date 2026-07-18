# Proyecto Transfer Learning MIAS

Hemos creado este repositorio con la finalidad de brindar un espacio de fácil acceso para el profesor y/o cualquier persona que desee verificar el proyecto y lo establecido, evitando un proceso de transferencia de archivos que podría llegar a ser más engorroso que útil.

**Aclaraciones principales**

El primer modelo (el cual fue entregado) resultó demostrar las limitaciones del conjunto de datos establecido, y del hardware con el que se contaba para el entrenamiento, por lo que proponemos una re-verificación del modelo, haciendo enfásis principalmente en:

A) Data Augmentation: El principal problema fue la cantidad de datos, aún con un proceso que aumentaba la cantidad de datos, este no fue suficiente para entrenar un modelo eficiente. Nuestra propuesta es maximizar qué tanta eficacia podemos conseguir exprimiendo al máximo profesos de Data Augmentation mucho más agresivo, con la finalidad de mejorar el modelo.

B) Hardware: Hemos decidido mover el entrenamiento para lograr trabajar con mayores resoluciones. Colab Free y el Hardware local nos permite trabajar como máximo con 16gb de VRAM, por lo que moveremos el entrenamiento a Colab PRO, usando sus 40gb de VRAM para trabajar con el modelo.

**Referentes**
Nuestro referente principal es: https://huggingface.co/abdullahtahir/resnet50-mammography-birads  obtuvo un 86.32% de accuracy con un dataset de 5662 imágenes. ¿Qué tanto podremos acercarnos con un dataset 18 veces menor? 
