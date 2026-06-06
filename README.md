# 🌍 Global GDP & Unemployment Dashboard — Power BI

> Macroeconomic dashboard built in Power BI analyzing global GDP and 
> unemployment trends across continents, countries, and decades. 
> Covers employment by sector, GDP per capita, population growth, 
> and dominant sector classification with Azure Maps integration.

---

## 📌 Overview

This dashboard provides a global macroeconomic view across three analytical
dimensions: general panorama of GDP, unemployment and population KPIs;
temporal growth trends (YoY); and continental/country participation rankings.
Built with advanced DAX patterns, HTML Content KPI cards, Azure Maps visual,
and slicers for Año, Continente, Década, and País.

---

## 📊 Dashboard Pages

| Page | Focus |
|------|-------|
| 🌐 Panorama General | GDP, unemployment, population, sector dominance by continent |
| 📅 Temporal | YoY growth trends — GDP, unemployment, population |
| 🏆 Participación | Country and continent rankings by GDP, employment, and population |

---

## 📐 DAX Measures

### 📊 Medidas Base
| Measure | Description |
|---------|-------------|
| `PIB Total` | Total GDP across selected filters |
| `PIB Promedio` | Average GDP per country |
| `PIB Per Capita Promedio` | Average GDP per capita |
| `PIB Total (Max año)` | Total GDP for the most recent year available |
| `Desempleo Promedio` | Average unemployment rate |
| `Poblacion` | Population for selected filters |
| `Poblacion Total` | Total global population |
| `Sector agricultura Promedio` | Average agricultural employment share |
| `Sector Industrial Promedio` | Average industrial employment share |
| `Sector Servicios Promedio` | Average services employment share |
| `Recuento Sector Dominante` | Country count per dominant sector |
| `KPI Sector Dominante por Continente` | Dominant sector label per continent |

---

### 🃏 HTML — KPI Cards
| Measure | Description |
|---------|-------------|
| `KPI PIBpc HTML` | Styled card — GDP per capita value |
| `KPI PIB PC Promedio HTML` | Styled card — average GDP per capita |
| `KPI Desempleo HTML` | Styled card — average unemployment rate |
| `KPI Poblacion HTML` | Styled card — total population |
| `KPI País Top 1 PIB Per Cápita (HTML)` | Styled card — top country by GDP per capita |
| `KPI País Mayor Población (HTML)` | Styled card — most populous country |
| `KPI Empleo Top 1 por Sector (HTML)` | Styled card — top country per employment sector |
| `KPI Top 1 Desempleo Promedio (HTML)` | Styled card — country with highest unemployment |

---

### 📅 Temporal
| Measure | Description |
|---------|-------------|
| `año_anterior` | Prior year reference for YoY calculations |
| `Crecimiento YoY PIB` | Year-over-year GDP growth rate |
| `Crecimiento PIB Per Capita` | Year-over-year GDP per capita growth |
| `Crecimiento Desempleo` | Year-over-year unemployment change |
| `Crecimiento Poblacion` | Year-over-year population growth |

---

### 🏆 Rank & Top N
| Measure | Description |
|---------|-------------|
| `Rank PIB` | Country ranking by total GDP |
| `Rank PIB Per Capita` | Country ranking by GDP per capita |
| `Rank Desempleo` | Country ranking by unemployment rate |
| `Rank Sector Industrial` | Country ranking by industrial employment |
| `Rank Sector Primario` | Country ranking by agricultural employment |
| `Rank Sector Servicio` | Country ranking by services employment |
| `Top 1 País PIB Per Capita` | Country with highest GDP per capita |
| `Top 1 País Desempleo Promedio` | Country with highest unemployment |
| `Top 1 Mayor Poblacion` | Most populous country |
| `Top 1 Continente Empleo Sector I...` | Top continent by industrial employment |
| `Top 1 Continente Empleo Sector P...` | Top continent by agricultural employment |
| `Top 1 Continente Empleo Sector S...` | Top continent by services employment |
| `Top 10 paises PIB` | Top 10 countries by total GDP |
| `Top 10 paises PIB Per Capita` | Top 10 countries by GDP per capita |
| `Top 10 Paises Desempleo` | Top 10 countries by unemployment rate |
| `Top 10 Paises Empleo Sector Indu...` | Top 10 by industrial employment share |
| `Top 10 Paises Empleo Sector Prim...` | Top 10 by agricultural employment share |
| `TOP 10 Paises Empleo Sector Servi...` | Top 10 by services employment share |

---

## 🛠 Tech Stack

| Tool | Usage |
|------|-------|
| Power BI Desktop | Dashboard design and publishing |
| DAX | All calculated measures, rankings, and KPIs |
| Azure Maps | Geographic GDP visualization by country |
| HTML Content (DAX) | Custom styled KPI cards |
| SQL Server | Data source and transformations |
| Python | ETL pipeline and data preparation |

---

## 📁 Repository Structure

```
global-gdp-unemployment-powerbi/
│
├── assets/
│   ├── panorama-general.png
│   ├── temporal.png
│   └── participacion.png
│
├── dax/
│   └── measures.md
│
├── model/
│   └── model.png
│
└── README.md
```

---

## 📸 Preview

> Screenshots of each dashboard page go here.

---

## 👤 Author

**Diego Torres Andrade**
Systems Engineering Student — Universidad Privada del Norte
Specialization: Data Analytics & Business Intelligence

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/tu-perfil)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)](https://github.com/tu-usuario)
