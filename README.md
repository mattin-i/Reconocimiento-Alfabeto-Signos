# Reconocimiento-Alfabeto-Signos
Proyecto de reconocimiento del alfabeto español de signos por medio de Deep Learning.

Por Sara Cristina Valle, Mattin Irigoien y Juan Campos.
Tutor : Carlos Santana Vega

<p align="center">
    <img src="ejemplo.gif", width="450">
</p>

## Introducción
### Misión
Hemos buscado implementar una solución sencilla que facilite el aprendizaje del abecedario dactilológico en tiempo real.
### Visión
Una solución que además sea accesible e inclusiva para todos. Permitiendo que estemos socialmente más unidos.
### Valores
Demostrar que una discapacidad del habla como una afasia o  una agnosia no son una barrera para la autonomía e independencia de la persona que vive con ella.

## Dataset

Hemos sacado el dataset de diferentes proyectos de Kaggle. El dataset principal y en el que nos basamos es uno del abecedario español de chile. Como el dataset no era muy grande intentamos sacar imagenes de otros dataset de otros idiomas cuyas letras coinciden con nuestro dataset principal

https://www.kaggle.com/bpablo27/abecedario-lenguaje-de-seas-chilenoespaol (Dataset principal)

https://www.kaggle.com/jordiviader/american-sign-language-alphabet-static

https://www.kaggle.com/danrasband/asl-alphabet-test

https://www.kaggle.com/grassknoted/asl-alphabet

## Pre-requisitos
Para ejecutar el proyecto, necesitas las siguientes librerías: Tensorflow, OpenCV, Numpy, Pandas, Matplotlib, Seaborn y Sklearn.
Si lo  prefieres puedes ejecutarlo desde la plataforma Google Colab, donde no necesitas instalar las librerías.

Está pensado para ejecutar desde Colab, por lo que el archivo 'Reconocimiento Lengua de Signos.ipynb' tiene una sección final donde poder probar el modelo en tiempo real con la webcam. Si quieres ejecutarlo en local, ejecuta el archivo 'VideoDetection.ipynb'
