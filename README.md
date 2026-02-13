# Modelo Predictivo de Demanda de Tickets

Este proyecto utiliza varios modelos de Machine Learning y Deep Learning para predecir la demanda diaria de tickets.

## Modelos Implementados

Se han implementado y evaluado los siguientes modelos:
- **Estadísticos**: ARIMA, SARIMAX
- **Machine Learning**: Random Forest, SVR (Support Vector Regression)
- **Deep Learning**: LSTM, GRU

El análisis comparativo y los resultados se pueden encontrar en los notebooks de Jupyter. El notebook `Modelo_Prediccion_PICOS.ipynb` contiene la comparativa inicial y `Modelo Ajustado.ipynb` contiene el análisis refinado con los mejores modelos.

## Visualizaciones

- **`fig1_tradicionales.png`**: Comparativa de modelos estadísticos (ARIMA, SARIMAX).
- **`fig2_ml.png`**: Comparativa de modelos de Machine Learning (Random Forest, SVR).
- **`fig3_dl.png`**: Comparativa de modelos de Deep Learning (LSTM, GRU).
- **`fig4_final.png`**: Comparativa de los 3 mejores modelos.

## Instalación

Sigue estos pasos para configurar el entorno de desarrollo.

**1. Crear un entorno virtual:**

```bash
python -m venv .venv
```

**2. Activar el entorno virtual:**

*   En Windows:
    ```powershell
    .venv\Scripts\activate
    ```
*   En macOS y Linux:
    ```bash
    source .venv/bin/activate
    ```

**3. Instalar las dependencias:**

Asegúrate de tener pip actualizado y luego instala los paquetes desde `requirements.txt`.

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Uso

Una vez que el entorno virtual está activado y las dependencias instaladas, puedes ejecutar el servidor de Jupyter Notebook:

```bash
jupyter notebook
```

Esto abrirá una pestaña en tu navegador donde podrás abrir y ejecutar los notebooks:
- `Modelo_Prediccion_PICOS.ipynb`
- `Modelo Ajustado.ipynb`

## Desactivar el entorno virtual

Cuando hayas terminado, puedes desactivar el entorno virtual con el comando:

```bash
deactivate
```
