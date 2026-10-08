# Lucas Ceccatto

**Economics · Financial Markets · Software**

I'm a final-year student at the Federal Institute of Paraná (IFPR), Brazil, where I study Business Administration, and the founder of [Ireon](https://ireon.co), an independent research and technology venture focused on financial markets.

My interests lie at the intersection of economics, quantitative finance, and software engineering, particularly global macro, econometrics, financial data infrastructure, and investment research.

I enjoy working on problems that move between theory and implementation: developing hypotheses, building the infrastructure to test them, and understanding what the evidence actually tells us.

## What I'm working on

### Ireon | Quant Labs & Algorithms

Developing and researching systematic investment strategies, quantitative models, and portfolio analytics.

My work involves backtesting, strategy validation, portfolio construction, risk analysis, and studying market behavior around earnings and expectations.

### Ireon | Internal Data Layer

Building the data infrastructure supporting Ireon's internal research systems.

Current development includes:

- **Global Prices:** Historical market data infrastructure focused on consistent pricing, adjustments, normalization, and a straightforward Python interface.
- **Point-in-Time Data Layer:** Historical data management designed to preserve information availability, temporal integrity, and reproducibility in quantitative research.

The guiding principle is simple: **complexity should live inside the infrastructure, not in the researcher's code.**

The intended Python interface reflects this philosophy:

```python
prices("MSFT")

prices("MSFT", start="2025-01-01", adjusted=True)
```

No unnecessary client initialization, provider-specific identifiers, or complex method chains. Data normalization, source resolution, and provenance are handled internally, keeping the research interface minimal.

### Ireon | BYOD Data Layer

A separate data infrastructure project focused on integrating externally supplied financial datasets.

The architecture emphasizes adaptability, standardized access, provider integration, and reliable data handling across different sources.

### Ireon | Public Equities

Equity and portfolio research combining fundamental analysis, financial modeling, and quantitative methods to evaluate companies and investment opportunities.

## Economics & Research

Beyond software development, I'm interested in economic history, international economics, industrial policy, and the relationship between institutions, markets, and economic development.

My current independent research examines rare-earth supply chains, resource endowments, industrial development, and the geopolitical dimensions of critical minerals.

I'm particularly interested in bringing empirical analysis and econometrics into broader historical and economic questions.

---

**[Ireon](https://ireon.co)**

*Most of Ireon's core development repositories are private.*
