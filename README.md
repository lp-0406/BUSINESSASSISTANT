# RetailIQ: FMCG Analytics & Decision Support Dashboard

## Introduction

RetailIQ is a data analytics platform developed to help FMCG businesses monitor sales performance, inventory movement, promotional campaigns, and regional trends through an interactive dashboard.

The application consolidates data from multiple business sources and transforms it into actionable insights that can support operational and strategic decision-making.

---

## Key Capabilities

### Business Performance Monitoring

* Track overall revenue generation
* Monitor product sales volume
* View store and product statistics
* Analyze performance across regions

### Product & Sales Insights

* Identify best-performing products
* Compare category-level sales contribution
* Explore revenue distribution patterns
* Understand product-wise performance trends

### Promotion Evaluation

* Measure the impact of promotional campaigns
* Compare promotional and non-promotional sales
* Study discount influence on revenue generation
* Evaluate campaign effectiveness

### Inventory Tracking

* Monitor stock availability
* Detect stockout situations
* Review inventory movement
* Analyze closing stock levels

### Interactive Visualizations

* Revenue trend charts
* Regional performance dashboards
* Category distribution analysis
* Hierarchical business visualizations
* Comparative analytical views

---

## Data Sources

The dashboard integrates information from four datasets:

### 1. Sales & Promotion Records

Contains transactional and campaign-related information such as:

* Sales period
* Product identifiers
* Store identifiers
* Units sold
* Revenue generated
* Promotion details
* Discount percentages

### 2. Inventory Records

Includes:

* Opening inventory
* Incoming stock
* Units sold
* Remaining stock
* Stockout indicators

### 3. Product Information

Stores metadata related to:

* Product names
* Brands
* Categories
* Subcategories
* Packaging specifications
* Pricing details

### 4. Store Information

Contains:

* Store names
* Locations
* Regions
* Store formats

---

## Technology Stack

| Component            | Technology   |
| -------------------- | ------------ |
| Frontend Dashboard   | Streamlit    |
| Data Processing      | Pandas       |
| Numerical Operations | NumPy        |
| Visualization        | Plotly       |
| Programming Language | Python       |
| Version Control      | Git & GitHub |

---

## Setup Instructions

### Clone Repository

```bash
git clone <repository-url>
cd fmcg-ai-business-assistant
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Application

```bash
streamlit run app.py
```

The dashboard will open automatically in your browser after startup.

---

## Project Directory

```text
fmcg-ai-business-assistant/

├── app.py
├── check_columns.py
├── requirements.txt
├── README.md
├── sales_promotions.csv
├── inventory.csv
├── product_master.csv
└── store_master.csv
```

---

## Business Benefits

* Faster access to operational insights
* Improved inventory visibility
* Better understanding of product performance
* Simplified reporting workflows
* Enhanced decision support through visual analytics

---

## Potential Enhancements

Future versions may include:

* Predictive sales forecasting
* Demand estimation models
* AI-powered query assistant
* Real-time database connectivity
* Role-based access control
* Cloud deployment support
* Automated reporting features

---

## Academic Context

This project demonstrates the application of data analytics, dashboard development, business intelligence concepts, and visualization techniques within the FMCG domain.

---

## License

This project is intended for educational and learning purposes.
