# Proyecto de Análisis de Datos – Exportación Minera 2025

## Descripción del Proyecto
Las exportaciones de cobre constituyen un pilar estratégico para la economía peruana, consolidando al país como uno de los principales productores a nivel mundial. Según la Sociedad Nacional de Minería, Petróleo y Energía (SNMPE, 2025), las exportaciones mineras peruanas alcanzaron US$ 61 849 millones, de los cuales aproximadamente US$ 28 130 millones correspondieron al cobre, evidenciando su relevancia dominante dentro del sector exportador nacional.

Para un análisis detallado de las exportaciones de cobre correspondiente a la partida arancelaria 7407100000 durante 2025, se utilizó información de **ADEX Data Trade**, que consolida registros oficiales de exportación incluyendo variables como valor FOB, peso neto y bruto, cantidad, empresas exportadoras, agente de aduana, puerto de embarque y país de destino. Esta información permite identificar patrones de comercialización, concentración empresarial, tendencias mensuales y eficiencia logística en los envíos hacia los principales mercados, incluyendo América del Norte.

Según la fuente de noticias **RPP Noticias** (Alarcón, 2026), las exportaciones mineras peruanas alcanzaron un récord histórico en 2025, confirmando que el cobre representa la mayor proporción dentro del sector y subrayando su impacto estratégico en la economía nacional.

## Tecnologías y Herramientas
- **Base de datos relacional:** SQL Server
- **Lenguaje de programación:** Python 3.13.13
- **Visualización y reportes:** Power BI, Excel
- **Control de versiones:** Git / GitHub
- **Documentación:** Markdown (.md)

---

## Estructura del Proyecto
```text
exportacion_minera_project/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
│
├── notebooks/
│   ├── eda/
│   ├── modeling/
│   └── dashboards/
│
├── src/
│   ├── extract/
│   ├── transform/
│   ├── analyze/
│   └── visualize/
│
├── reports/
│   ├── informe/
│   │   ├── informe_exportacion_minera.md
│   │   └── anexos/
│   ├── excel/
│   └── powerbi/
│
├── tests/
├── docs/
├── config/
├── requirements.txt
└── README.md