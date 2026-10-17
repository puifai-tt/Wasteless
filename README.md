# Wasteless: Sales Forecasting and Food Waste Prevention Platform

Wasteless is a web-based operational dashboard engineered for cafés and restaurants to optimize inventory management, accurately predict daily demand, and systematically prevent food waste. The platform correlates historical sales data with external environmental factors—such as weather patterns and local events—to generate actionable procurement and sales forecasts.

---

## Key Features

- **Executive Analytics Dashboard**
  Provides high-level operational visibility through key performance indicators (KPIs), including revenue trends, waste reduction metrics, forecast accuracy backtests, and real-time alerts for ingredients nearing expiration.

- **Predictive Demand Forecasting Engine**
  Calculates item-level sales projections by analyzing historical Point of Sale (POS) data against weather forecasts, day classifications (weekday vs. weekend/holiday), and localized event impacts.

- **Automated Bill of Materials (BOM) & Procurement**
  Generates supplier-specific reorder recommendations by matching forecasted dish volume against recipe formulations, current inventory levels, and configurable safety stock buffers.

- **Waste Mitigation & Promotional Campaign Engine**
  Identifies surplus stock nearing shelf-life limits and recommends promotional pricing strategies that maximize ingredient utilization while enforcing minimum profit margin thresholds.

- **Inventory and Recipe Formulation Management**
  Tracks raw material inventory across batches, monitors shelf-life status, calculates recipe Costs of Goods Sold (COGS), and supports full data import/export via CSV format.

- **Artificial Intelligence Assistant**
  Integrates Google's Gemini API to offer an interactive natural language interface capable of querying operational data, inventory risks, and stock recommendations.

- **Digital Signage & Operational Briefings**
  Features a built-in preview interface for in-store promotional displays (Store TV) and automated daily briefing summaries for store managers.

---

## Technical Architecture

- **Frontend Framework:** Native HTML5, Modern JavaScript (ES6+)
- **Styling & Layout:** Tailwind CSS
- **Data Visualization:** Chart.js
- **CSV Data Ingestion:** PapaParse
- **Artificial Intelligence Engine:** Google Gemini API Integration

---

## Installation and Deployment

This application operates as a client-side Web Application and requires no server-side build steps or database deployment.

### Local Development

1. Clone the repository:
   ```bash
   git clone [https://github.com/puifai-tt/wasteless.git](https://github.com/your-username/wasteless.git)
