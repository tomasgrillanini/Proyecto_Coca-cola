# 🥤 Coca-Cola USA — Ventas, Mix y Logística (2022–2024)

Dashboard integral en Power BI que analiza el comportamiento comercial,
nutricional y logístico de Coca-Cola y sus marcas en el mercado de
Estados Unidos, sobre un dataset de ~4.500 registros y 20 variables.

## 🎯 Objetivo

Convertir el registro transaccional de ventas en un sistema de
conocimiento accionable que responda: ¿qué vende, dónde, cómo y por qué?
El tablero permite identificar qué combinación de región, marca,
atributos nutricionales y logística explica las diferencias de
desempeño sostenidas en el tiempo.

## 🔍 Hipótesis principales

- Ciertas regiones/ciudades concentran de forma desproporcionada
  la facturación y el volumen (H1)
- El mix sin azúcar y bajas calorías gana participación en
  determinadas zonas y minoristas (H4)
- Los formatos y tipos de envase explican diferencias en
  rotación y margen operativo (H5)
- Menores días de entrega se correlacionan con mejor
  performance comercial (H9)

## 📊 KPIs del tablero

| KPI | Descripción |
|---|---|
| Ventas Totales (USD) | Facturación agregada por región, marca y período |
| Unidades Vendidas | Volumen por tipo de producto y envase |
| Precio Promedio Ponderado | Precio neto de mezcla |
| Margen Operativo % | Segmentado en bajo / medio / alto |
| Días para Entrega (promedio) | Por empresa de reparto y geografía |
| Índice de Entrega Rápida | % de pedidos con días ≤ P25 |
| Mix Nutricional | % sin azúcar, % con edulcorantes, calorías promedio |

## 🗂️ Estructura del dashboard

| Solapa | Descripción |
|---|---|
| Resumen Ejecutivo | KPIs globales, ranking de minoristas y tendencia YoY |
| Mercado & Cobertura | Análisis geográfico por región, estado y ciudad |
| Portafolio & Nutrición | Mix de marcas, envases y atributos nutricionales |
| Logística & Servicio | Días de entrega y desempeño por empresa de reparto |
| 2024 Performance | Cierre del período y comparativa interanual |

## 🛠️ Herramientas y técnicas

- **Power BI** — modelado estrella, dashboard interactivo con
  navegación global → intermedio → detalle
- **DAX** — medidas de margen operativo, índice de entrega rápida,
  participación de portafolio y mix nutricional
- **Power Query** — limpieza, transformación y validación del dataset
- **Excel** — inspección preliminar y validación de valores atípicos
- **Metodología SMART** — definición de objetivos, KPIs y
  resultados esperados

## 📁 Estructura del proyecto
```
├── INFORME_COCACOLA.pdf          # Documentación completa del proyecto
├── dashboard_cocacola.pbix       # Archivo Power BI
└── README.md
```

## 👤 Autor

**Tomás Grillanini** — Data Analyst  
[LinkedIn](#) · [Portfolio](#)
