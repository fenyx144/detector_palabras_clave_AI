# 🔑 Detector de Palabras Clave con IA (Google Colab)

Un proyecto sencillo que utiliza **KeyBERT** para extraer palabras clave de cualquier texto. Este proyecto está diseñado para ejecutarse fácilmente en **Google Colab**.

## 🚀 Funcionalidades
- Extrae palabras clave relevantes de textos largos o cortos.
- Personaliza:
  - El rango de n-gramas (1 palabra, frases de 2 palabras, etc.).
  - La cantidad de palabras clave a detectar.

## 📋 Requisitos
- Ejecútalo en [Google Colab](https://colab.research.google.com/) con Python 3.
- Instala las bibliotecas necesarias directamente en Colab:

```bash
!pip install keybert
```

## 🤔 ¿Cómo funciona?
Carga del texto: Escribe o pega tu texto en el bloque de código.
Personaliza parámetros:
Rango de n-gramas: Decide si quieres palabras clave individuales o frases.
Número de palabras clave: Determina cuántas palabras clave deseas extraer.
Ejecuta el código: KeyBERT analiza el texto y devuelve las palabras clave con su relevancia.

## ▶️ Ejecución
Abre el archivo detector_palabras_clave_colab.ipynb en Colab.
Ejecuta las celdas para instalar las dependencias y ejecutar el código.
Personaliza el texto y los parámetros según tus necesidades.

## 🌟 Ejemplo
Texto de entrada:

```
La inteligencia artificial está revolucionando múltiples industrias, desde la atención médica hasta la educación.
```

Salida esperada:

```
🔑 Palabras clave detectadas:
- inteligencia artificial (Relevancia: 0.85)
- atención médica (Relevancia: 0.79)
- educación (Relevancia: 0.72)
```

## 📜 Licencia
Este proyecto está licenciado bajo la MIT License.