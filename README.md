# Challenge_TelecomX_Parte2

1. El propósito del análisis realizado, nos permitira analizar los datos necesarios para comprender porque la empresa enfrenta una alta tasa de cancelaciones. Lo que es un problema crítico que afecta directamente los  ngresos recurrentes de la empresa Telecom X. Se realiza el análisis con el proposito de tomar la decisión que más convenga para la empresa y así evitar las cancelaciones de los clientes.

2. La estructura del proyecto y organización de los archivos. 
Se utilizo un libro de Google Colab para realizar el análisis de datos, así como un archivo tipo csv el cual contenia los datos a analizar.

3. Descripción del proceso de preparación de los datos:
- Clasificación de las variables en categóricas y numéricas.
<img width="603" height="679" alt="image" src="https://github.com/user-attachments/assets/b3e249cc-438d-4087-b190-27a8fee3fba9" />


- Etapas de normalización o codificación.
<img width="1069" height="400" alt="image" src="https://github.com/user-attachments/assets/79d8c9c9-b62b-4850-8ee8-92062df6e1ab" />


- Separación de los datos en conjuntos de entrenamiento y prueba.
<img width="982" height="720" alt="image" src="https://github.com/user-attachments/assets/f2712e9b-f1e3-41fe-a830-e70c7386b588" />


- Justificaciones para las decisiones tomadas durante la modelización.
<img width="878" height="390" alt="image" src="https://github.com/user-attachments/assets/5ca8696d-6bc0-47ce-ab12-a787694714d9" />



4. Ejemplos de gráficos e insights obtenidos durante el análisis exploratorio de datos (EDA).
<img width="715" height="576" alt="image" src="https://github.com/user-attachments/assets/bcdce56b-91fd-4563-8d16-5b83cc996b1f" />

<img width="956" height="595" alt="image" src="https://github.com/user-attachments/assets/7e861440-8ef1-4f1e-b324-e105a633724b" />

<img width="949" height="590" alt="image" src="https://github.com/user-attachments/assets/731e1e6e-3a0b-4e81-a510-24b2e69258a6" />

<img width="938" height="682" alt="image" src="https://github.com/user-attachments/assets/bb2d3e22-6f8a-4b76-87f5-619b23c37c8f" />



5. Instrucciones para ejecutar el cuaderno
- Acceder al archivo o notebook, seleccionar donde indica "Entorno de ejecución" y despues dar click en "Ejecutar todo", lo cuál mostrara todos los datos obtenidos del challenge.
l<img width="1342" height="645" alt="image" src="https://github.com/user-attachments/assets/6e3b419d-e04c-438a-bf12-9d1593ae5bdc" />

- Como cargar los datos al cuaderno:
En el icono de una carpeta o folder dar click, luego dar click en el icono de una pagina con una flecha apuntando hacia arriba llamado "Cargar archivos de almacenamiento de sesión" o ubicar el puntero encima del icono para identificar el nombre.
<img width="422" height="449" alt="image" src="https://github.com/user-attachments/assets/b1757b72-35e2-44ce-91d8-514565a383ec" />


- Bibliotecas utilizadas para el análisis de datos:
import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

from imblearn.over_sampling import SMOTE

from sklearn.model_selection import train_test_split

from sklearn.preprocessing import StandardScaler

from sklearn.linear_model import LogisticRegression

from sklearn.metrics import classification_report, confusion_matrix, roc_auc_score, ConfusionMatrixDisplay

from sklearn.model_selection import train_test_split

from sklearn.metrics import classification_report, roc_auc_score

from sklearn.ensemble import RandomForestClassifier

from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score, confusion_matrix, ConfusionMatrixDisplay
