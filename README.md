# MACI-proyecto_final
sistema comparación modelos

<h2>Descripción</h2>
<p>Este repositorio contiene el código fuente Python para realizar un backtesting comparativo entre dos modelos: el modelo actual y un nuevo modelo. El notebook backtesting.ipynb detalla el proceso completo, desde la carga de los datos de los modelos hasta la generación de un archivo de salida con los resultados de la comparación.</p>

<h2>Requisitos</h2>
<p>Python: Versión 3.12 o superior.<br>
Librerías: Pandas, NumPy, SciPy, matplotlib, openpyxl, sklearn</p>

<h2>Estructura del repositorio</h2>
<p>backtesting.ipynb: Notebook principal con el código de backtesting.<br>
modelo_actual.xlsx: Ejemplo de archivo de entrada para el modelo actual.<br>
modelo_nuevo.xlsx: Ejemplo de archivo de entrada para el nuevo modelo.<br>
output.txt: Ejemplo de archivo de salida generado por el programa.</p>

<h2>Instrucciones de uso</h2>
<ol>
<li>Clonar el repositorio:</li>
git clone https://github.com/ssalgado2017/MACI-proyecto_final.git</p>

<li>Crear un entorno virtual (opcional pero recomendado):</li>
python -m venv venv
source venv/bin/activate

<li>Instalar las dependencias:</li>
pip install -r requirements.txt

<li>Preparar los archivos de entrada:</li>
Reemplaza los archivos modelo_actual.xlsx y modelo_nuevo.xlsx con tus propios datos. Asegúrate de que tengan el mismo formato que los ejemplos proporcionados.

<li>Ejecutar el notebook:</li>
jupyter notebook backtesting.ipynb

</ol>

<h2>Explicación del proceso</h2>
<p>El notebook cargará los datos de los dos modelos, realizará los cálculos necesarios y generará un archivo de salida llamado output.txt que contendrá los resultados de la comparación.</p>

<h2>Ejemplos</h2>
<p>Los archivos modelo_actual.xlsx, modelo_nuevo.xlsx y output.txt proporcionados sirven como ejemplos de cómo deben ser tus archivos de entrada y salida. Puedes utilizarlos como plantilla para crear tus propios archivos.</p>
