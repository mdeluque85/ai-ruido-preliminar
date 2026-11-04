# Preliminary noise area of influence of hydrocarbon blocks in Colombia

Web application and spreadsheet that estimate a preliminary noise area of influence for a hydrocarbon exploration block. The result is the block plus a band as wide as the largest distance r* of the spreadsheet.

The method is described in the article by Pérez et al. (manuscript in preparation).

## How to use it

1. Open `calculator/Noise_influence_area_calculator.xlsx`, follow the Guide sheet, and save the file.
2. Open the application (`index.html`).
3. Load the saved spreadsheet and the block limit (a zipped shapefile with its .prj, the loose files, or a GeoJSON).
4. Review the criteria and download the polygon as a shapefile in EPSG:9377, KML or GeoJSON.

The application runs in the browser. Files stay on your device.

## Limits

- Preliminary result for scoping. It does not replace the full noise model that the 2026 Colombian methodology requires.
- Flat terrain and warm climates (20 to 32 °C), such as the Llanos Orientales.
- The band around a block was not tested against a full model.

---

# Área de influencia preliminar por ruido de bloques de hidrocarburos en Colombia

Aplicación web y hoja de cálculo para estimar el área de influencia preliminar por ruido de un bloque de exploración de hidrocarburos. El resultado es el bloque más una franja tan ancha como la mayor distancia r* de la hoja de cálculo.

El método se describe en el artículo de Pérez et al. (manuscrito en preparación).

## Cómo usarla

1. Abra `calculator/Calculadora_area_influencia_ruido.xlsx`, siga la hoja Guia y guarde el archivo.
2. Abra la aplicación (`index.html`).
3. Cargue la hoja guardada y el límite del bloque (shapefile en .zip con su .prj, los archivos sueltos o un GeoJSON).
4. Revise los criterios y descargue el polígono en shapefile EPSG:9377, KML o GeoJSON.

La aplicación corre en el navegador. Los archivos no salen de su equipo.

## Límites

- Resultado preliminar para definir el alcance. No reemplaza el modelo completo de ruido que exige la metodología colombiana de 2026.
- Terreno plano y clima cálido (20 a 32 °C), como los Llanos Orientales.
- La franja alrededor de un bloque no se probó contra un modelo completo.
