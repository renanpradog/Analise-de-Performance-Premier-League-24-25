# ⚽ Análise da Premier League 2024/25 – Dashboard em Power BI

Este é um projeto de visualização e análise de dados desenvolvido com Power BI, com foco na temporada 2024/25 da Premier League.

## 📊 Objetivo

Explorar o desempenho ofensivo dos jogadores da liga, indo além das métricas tradicionais (como gols e assistências totais) e aplicando indicadores de eficiência como **Participações por 90 minutos**.

## 📁 Dados

A base foi obtida no [Kaggle](https://www.kaggle.com/) com estatísticas detalhadas dos jogadores da temporada 2024/25, contendo:

- Minutos jogados  
- Gols  
- Assistências  
- Nacionalidade  
- Posição  
- Clube  

## 🧠 Métricas criadas com DAX

- `Gols por 90 = DIVIDE([Total Gols], [Total Minutos]) * 90`
- `Assistências por 90 = DIVIDE([Total Assistências], [Total Minutos]) * 90`
- `Participações por 90 = [Gols por 90] + [Assistências por 90]`

## 📌 Visuais incluídos no dashboard

- Participações por 90 min (Top 10 jogadores)
- Distribuição de Gols por Posição
- Total de Gols por Clube
- Mapa interativo de nacionalidades
- KPIs: Total de Jogadores, Gols, Assistências, Minutos médios

## 🛠️ Ferramentas usadas

- Power BI Desktop
- DAX

## 📷 Visual do Dashboard

![Dashboard](./Dashboard.pdf)

## 🚀 Autor

**Renan Gonzalez**  
[LinkedIn](https://www.linkedin.com/in/renan-gonzalez333)
