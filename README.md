# PyTorch predicción de baja (Churn)
Este código corresponde al video [Youtube]() en el cual muestro los fundamentos básicos para poder construir una red neuronal utilizando **PyTorch**. El set de datos que se utiliza proviene de [Kaggle](https://www.kaggle.com/datasets/shubh0799/churn-modelling) y se llama "Churn Modelling" el cual es una base de datos de 10,000 registros y 14 columnas. **Las variables son información de distintos usuarios de tarjetas de crédito y la columna de la variable destino es si el usuario de ese registro cancelo su cuenta bancaria o no**

Lo que se busca es generar un modelo el cual dadas las variables que tiene este set de datos pueda predecir si el cliente va a cancelar su cuenta o no.

## Requisitos
En cuanto a **hardware** no se requiere equipo especializado (Como una tarjeta de gráficos) ya que el modelo utilizado en este ejemplo es muy pequeño y un **CPU es capaz de correr el entrenamiento sin problema**. 
Sobre software se requiere tener instalado *Python 3.8 o mayor*, el instalador **pip o conda** para poder descargar a instalar las paqueterias de Python que se usaran, como PyTorch, sklearn, matplotlib etc.

## Configuración
Para poder hacer la instalación de las paqueterías requeridas y abrir el código se deben correr los siguientes comandos:
~~~
pip install -r requirements.txt
~~~
Una vez instalado solo se debe correr Jupyter para abrir el cuaderno
~~~
Jupyter notebook main.ipynb
~~~

